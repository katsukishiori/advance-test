#  飲食店予約アプリ  
飲食店を予約できるアプリ

##  作成した目的
会社で使いやすい飲食店予約サービスを持つため。  

##  アプリケーションURL  
開発環境:http://localhost/  
phpMyAdmin:http://localhost:8080/  
##  他のリポジトリ  

##  機能一覧
・会員登録機能  
・ログイン機能  
・ログアウト機能  
・飲食店お気に入り追加・削除機能  
・飲食店予約情報追加・削除機能  
・エリア・ジャンル・店名で検索できる機能  
・予約変更機能  
・評価機能  
・ストレージに画像保存機能

##  使用技術  
・PHP 7.4.9  
・Laravel 8.83.27  
・MySQL 


##  テーブル設計  
<img width="572" alt="スクリーンショット 2024-03-30 12 31 52" src="https://github.com/katsukishiori/advance-test/assets/145991391/5ab1e340-dea5-4ba8-81fd-4788d12b474c">

##  環境構築  
Dockerビルド  
1.ディレクトリの作成  
2.docker-compose.ymlの作成  
3.Nginxの設定  
4.PHPの設定  
5.MySQLの設定  
6.phpMyAdminの設定  
7.docker-compose up -d --build  

※MySQLは、OSによって起動しない場合があるのでそれぞれのPCに合わせてdocker-compose.ymlファイルを編集してください  

Laravel環境構築  
1.docker-compose exec php bash  
2.composer -vでcomposerがインストールできているか確認  
3.composer create-project "laravel/laravel=8.*" . --prefer-dist  
4.php artisan migrate  
5.php artisan db:seed  




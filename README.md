# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation
# mysql
* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

* rails s を起動する（docker version)
### docker-compose up

* DB作りたくなったら
### $ docker-compose run --rm app rake db:create

* マイグレーションしたくなったら
### $ docker-compose run --rm app rake db:migrate

* seed実行したくなったら
### $ docker-compose run --rm app rake db:seed

* コントローラー作成したくなったら(controller_nameを変更してどうぞ)
### $ docker-compose run --rm app rails generate controller controller_name

* Model作成したくなったら(model_nameを変更してどうぞ 引数にname:stringとかでnameカラムを作れます。)
### $ docker-compose run --rm app rails generate model model_name name:string 

* ルーティング変更したくなったら(config/routes.rbを編集後実行)
### $ docker-compose run --rm app rake routes

* dockerを止める
### $ docker stop sampleApp

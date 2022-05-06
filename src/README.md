# README

* How to start

クローンして下さい（winはwsl）

※winのみ
Dockerfileの username を自分の環境になおして下さい

docker-compose build を実行して下さい(win はsudoがひつようかも)

※winのみ
上記で直したusernameをもとにもどしてください（イメージから作るときは再度実行）

 docker-compose run web rails db:create を実行して下さい。

 docker-compose up -d で開始
 docker-compose down  で終了


* For Docker Container


* For Rails
  
  rails コマンドはコンテナに自分のアカウントで入ってから実行する
  docker-compose exec --user username web /bin/bash








This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

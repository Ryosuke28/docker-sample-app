# 起動前準備
$ docker-compose build
$ docker-compose run --rm rails bundle install
$ docker-compose run --rm rails yarn install
$ docker-compose run --rm rails bundle exec rails db:create db:migrate db:seed
$ docker-compose up -d rails

このあとホストのポート3000でアクセスできる


https://www.techpit.jp/courses/76


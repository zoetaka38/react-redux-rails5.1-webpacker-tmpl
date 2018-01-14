# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

- Docker
- docker-compose

* Configuration

```sh
docker-compose build
docker-compose run server rails webpacker:install
docker-compose run server rails webpacker:install:react
```

* Database creation

```sh
docker-compose run server rails db:create
```

* Database initialization

* How to run the test suite

```sh
docker-compose up
# another terminal
docker-compose exec server bash
# on the shell in the container
bin/webpack-dev-server
```

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


include ./.env

up:
	docker-compose up -d
build:
	docker-compose up -d --build
stop:
	docker-compose stop

migrate:
	docker-compose exec app /usr/local/bin/php artisan migrate
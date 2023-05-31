
include ./.env

app:
	docker-compose exec app bash
up:
	docker-compose up -d
build:
	docker-compose up -d --build
stop:
	docker-compose stop

migrate:
	docker-compose exec app /usr/local/bin/php artisan migrate
cache:
	docker-compose exec app php artisan cache:clear
	docker-compose exec app php artisan view:clear
	docker-compose exec app php artisan config:clear

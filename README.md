# docker-nginx-php-fpm-laravel

Run:
```
docker compose up -d nginx-server (start nginx-server, php-fpm and mysql)
docker compose down
```

Utility:
```
docker compose run --rm composer-util ...
docker compose run --rm artisan-util migrate
docker compose run --rm npm-util ...
```
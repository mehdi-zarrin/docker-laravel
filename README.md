* install laravel in src/ folder then run `docker-compose build && docker-compose up -d`
* it will create a default database `homestead`
* to run migration do: `docker exec php php /var/www/artisan migrate`
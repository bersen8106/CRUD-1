### Установка

установить PHP-7.3+

установить MySQL

установить Composer

cd /var/www

git clone https://github.com/bersen8106/CRUD-1 folder

cd folder

composer install

define database, APP_KEY in .env

php artisan migrate --seed

php artisan serve

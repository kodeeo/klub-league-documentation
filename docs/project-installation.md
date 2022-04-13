# Installation steps

```bash
git@github.com:kodeeo/klub-league.git
cp .env.example .env
composer update
php artisan key:generate
create database
In .env file add database name and user name(root)
php artisan migrate
php artisan db:seed
php artisan serve

```
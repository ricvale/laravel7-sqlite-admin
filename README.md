# laravel7-sqlite-admin
## Quick boilerplate: Laravel 7 + SQLite + Auth

### To do: 
* git clone https://github.com/ricvale/laravel7-sqlite-admin.git my_awesome_app
* Create .env file from .env.example, remove lines DB_* (lines 9-14), and instead add line: DB_CONNECTION=sqlite

#### Run from the root of your application these commands:
* composer install --no-scripts
* php artisan key:generate
* touch database/database.sqlite
* php artisan migrate

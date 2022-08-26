## Laravel Inventory
git clone 
cd laravel-sales
composer install
cp .env.example .env
php artisan migrate
php artisan key:generate
php artisan storage:link
php artisan serve
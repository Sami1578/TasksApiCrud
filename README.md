//require laravel sanctum
composer require laravel/sanctum

//publish sanctum files / add migration files
php artisan vendor:publish --provider="Laravel\Sanctum\SanctumServiceProvider"
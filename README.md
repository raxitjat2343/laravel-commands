# laravel-commands
only for remember things for laravel.

composer create-project laravel/laravel example-app
composer create-project --prefer-dist laravel/laravel test "8.*"

php artisan make:controller PostController --resource --model=Post

php artisan make:model Post

composer require laravel/ui
php artisan ui bootstrap




## Migration
        - php artisan make:migration create_users_table
        - php artisan make:migration add_votes_to_users_table --table=users

## Create Middileware:
         - php artisan make:middleware CheckAge

 ## Create Controller
          -  php artisan make:controller PhotoController --resource
          -  php artisan make:controller PhotoController --resource --model=Photo
          -  php artisan make:controller API/PhotoController --api
          -  php artisan make:controller ShowProfile --invokable

## Create Model
          php artisan make:model Flight
          php artisan make:model Flight --migration
          php artisan make:model Flight -m

## Create Observer
         php artisan make:observer UserObserver --model=User

## Create Command
         php artisan make:command SharesAlloted

## Create Request
         php artisan make:request StoreBlogPost
         php artisan make:rule Uppercase


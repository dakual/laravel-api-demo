## Create laravel new api project
```sh
composer create-project --prefer-dist laravel/laravel laravel-api-demo
```

## To create the Books model, we can run
This will create a Contact model and a migration file.<br>
> app/models/Books.php
> database/migrations/xxxxxx_create_books_table
```sh
php artisan make:model Books -m
```

## Migrating to Database
```sh
php artisan migrate
```

## Database Seeding
```sh
php artisan db:seed --class=BooksSeeder
```

## Creating the Controller
> app/Http/Controllers/BookController.php
```sh
php artisan make:controller BookController
```

## Running Laravel API Application
```sh
php artisan serve
```


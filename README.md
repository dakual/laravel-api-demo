## Create laravel new api project
```sh
composer create-project --prefer-dist laravel/laravel laravel-api-demo
```

## To create the Books model, we can run
This will create a Contact model and a migration file.<br>
> app/models/Books.php<br>
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

## Usage
These route binds functions to specific URL which is listed below:

GET /books, mapped to the index() method
GET /books/{id}, mapped to the show() method
POST /books, mapped to the store() method
PUT /books/{id}, mapped to the update() method
DELETE /books/{id}, mapped to the destroy() method


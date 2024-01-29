#  Book Rental Library

## Exercise 2: 

Expand the book rental library application to include functionality for users to view a list of books, and rent a book. This involves setting up a database, creating models and relationships, and handling form data securely.

## Installation

- Copy `.env.example` to `.env`
- Run `composer install`
- Run `php artisan key:generate --ansi`
- Run `php artisan migrate`
- Run `php artisan db:seed --class=GenresTableSeeder`
  
## Run Application

Run `php artisan serve` or visit project `public` directory from the browser.

Add some books: Management > Books > [Add new book]
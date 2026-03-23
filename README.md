# Technical CRUD API

A simple and clean CRUD application built with Symfony to manage products.

## Features

- Product list
- Create a product
- View product details
- Edit a product
- Delete a product
- Form validation
- Responsive UI with Bootstrap

## Tech Stack

- Symfony
- Doctrine ORM
- SQLite
- Twig
- Bootstrap

## Installation

Clone the repository:
git clone https://github.com/Oummy13/technical-crud-api.git
cd technical-crud-api


Install dependencies:
composer install

Run the project
Start the Symfony server:
symfony serve --no-tls

Then open in your browser:
http://127.0.0.1:8000/product/

## Database
This project uses SQLite (no setup required).

Run database migrations:
php bin/console doctrine:migrations:migrate

## Author

Oummoul Koulsouwi
Full-Stack Developer (Symfony / React)

GitHub: https://github.com/Oummy13
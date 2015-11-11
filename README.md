# Larangular
Laravel 5.1 + Angular Starter Projects



# Laravel 5.1 and AngularJS Starter Admin Panel Application

This is github repo for a starter application for an admin panel application featuring the modern Laravel PHP framework and AngularJS, front-end framework by Google. Download and install for building any web applications.


## Features!

- Admin panel with all function
  - Crud Function With Angular
  - Sign up Login Auth System
  - jwt Auth 
  - etc.


## Installation
```
git clone https://github.com/balitax/Larangular.git
```
```
composer install --prefer-dist
```
```

### Database Setup

Edit `.env.example` according to your environment and save as `.env`.
An application key can be generates with the command `php artisan key:generate`.

Run these commands to create the tables within the database you have already created.

```
php artisan migrate:install
```
```
php artisan migrate:refresh
```

## Run


To start the PHP built-in server:
```
php artisan serve
```

Now you can browse the site  [http://localhost:8080](http://localhost:8080). 🙌

## Requirements

- PHP >= 5.5
- Composer
- MySQL
- Tokenizer

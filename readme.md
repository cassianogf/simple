# Controle de Restaurantes - Backend

## Step 1: Minimum system requirements

Laravel utilizes [Composer](https://getcomposer.org/) to manage its dependencies. So, before using Laravel, make sure you have Composer installed on your machine.

## Step 2: Installation

In the project directory install the dependencies by running:

```
composer install
```

## Step 3: Generate the Application Key 

Rename the `.env.example` file in the project folder to `.env `

Generate the application key by running:

```
php artisan key:generate
```

## Step 4: Configuration

Open `.env` file and configure the database properties.

Cache the config file

```
php artisan config:cache
```

And migrate, to create database tables

```
php artisan migrate
```

## Step 5: Serve the application

Launch the server

```
php artisan serve
```

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

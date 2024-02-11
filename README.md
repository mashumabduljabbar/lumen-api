# LUMEN API

## Requirements

* PHP >= 8.0
* OpenSSL PHP Extension
* PDO PHP Extension
* Mbstring PHP Extension


## Create Project

``` bash
composer create-project --prefer-dist laravel/lumen lumen-api
```


## Changes

* Uncomment Facades and Eloquent in Line 26 - 28 at ./bootsrap/app.php
* Uncomment middleware and routeMiddleware in Line 75 - 81 at ./bootsrap/app.php
* Uncomment register in Line 94 - 96 at ./bootsrap/app.php
* Change APP_TIMEZONE to Asia/Jakarta at .env
* Cange LOG_CHANNEL to daily at .env
* DB Credential at .env

## Run Project

### Composer

``` bash
composer install
```


### PHP

``` bash
php -S localhost:8000 -t public
```

1. php: This is the command to execute PHP scripts from the command line.

2. -S localhost:8000: This option specifies the development server to be used and the port to be used. In this example, the development server will run on localhost (meaning it can only be accessed locally) and use port 8000. You can change this port as needed.

3. -t public: This option specifies the root directory of the application. In this example, the root directory is set to public. This means the server will execute the application from the public directory, which is generally a good security practice to only expose public files directly to users.

You can execute this command in the terminal or command prompt, and then access your Laravel Lumen application through http://localhost:8000 in a web browser.
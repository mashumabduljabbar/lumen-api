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
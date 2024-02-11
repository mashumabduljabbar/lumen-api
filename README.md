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

Mari kita breakdown bagian-bagian dari perintah tersebut:

1. php: Ini adalah perintah untuk menjalankan skrip PHP dari baris perintah.

2. -S localhost:8000: Opsi ini menentukan server pengembangan yang akan digunakan dan port yang akan digunakan. Dalam contoh ini, server pengembangan akan berjalan di localhost (artinya hanya dapat diakses secara lokal) dan menggunakan port 8000. Anda dapat mengganti port ini sesuai kebutuhan.

3. -t public: Opsi ini menentukan direktori root aplikasi. Dalam contoh ini, direktori root diatur ke public. Ini berarti server akan mengeksekusi aplikasi dari direktori public, yang umumnya merupakan praktik keamanan yang baik untuk mengatur hanya file-file publik yang dapat diakses langsung oleh pengguna.

Jadi, secara keseluruhan, perintah tersebut digunakan untuk menjalankan server pengembangan Laravel Lumen dengan konfigurasi tertentu untuk host dan port, dan dengan direktori root yang ditetapkan ke public. Anda dapat menjalankan perintah ini di terminal atau command prompt, dan kemudian dapat mengakses aplikasi Laravel Lumen Anda melalui http://localhost:8000 dalam browser.
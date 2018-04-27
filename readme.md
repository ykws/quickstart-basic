# Laravel Quickstart - Basic

![ScreenShot](https://i.imgur.com/fSt17Cul.png)

## Quck Installation

```
$ git clone https://github.com/ykws/quickstart-basic quickstart
$ cd quickstart
$ composer install
```

### SQLite configuration

```
$ touch database/database.sqlite
$ cp .env.example .env
```

Edit `.env`

```diff
+DB_CONNECTION=sqlite
 DB_HOST=127.0.0.1
-DB_DATABASE=homestead
-DB_USERNAME=homestead
-DB_PASSWORD=secret
```

### Artisan!

```
$ php artisan key:generate
$ php artisan migrate
$ php artisan serve
```

## Documatation

- [Database: Getting Started - Configuration (Laravel 5.5)](https://laravel.com/docs/5.5/database#configuration)
- [Complete Tutorial (Laravel 5.2)](https://laravel.com/docs/5.2/quickstart)
- [Help for Laravel 5.5](http://ykawashi7.hatenablog.com/entry/2017/10/20/012235)

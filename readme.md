<p align="center"><img src="https://laravel.com/assets/img/components/logo-passport.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/passport"><img src="https://travis-ci.org/laravel/passport.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/passport"><img src="https://poser.pugx.org/laravel/passport/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/passport"><img src="https://poser.pugx.org/laravel/passport/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/passport"><img src="https://poser.pugx.org/laravel/passport/license.svg" alt="License"></a>
</p>

## Introduction

Laravel Passport is an OAuth2 server and API authentication package that is simple and enjoyable to use.

## 本分支的修改内容

为 Passport 定义了专用的数据库连接名 `passport_database_connection` , 需要自行在配置文件 config/database.php 的  数组中配置.

    ```
    'connections' => [

        ...

        'passport_database_connection' => [
            ...
        ],
        
        ...
        
    ],
    ```
    
## Official Documentation

Documentation for Passport can be found on the [Laravel website](http://laravel.com/docs/master/passport).

## License

Laravel Passport is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).

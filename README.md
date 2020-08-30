# Laravel Blog

This application is blog system based on *Laravel 7.24*.

## Table of contents
 * [Setup](#setup)
 * [Status](#status)

## Setup

```console
foo@bar: laravel-blog $ cp .env.example .env
```

```console
foo@bar: laravel-blog $ docker-compose up -d --build
```

```console
foo@bar: laravel-blog $ docker-compose exec php cp .env.example .env
```

```console
foo@bar: laravel-blog $ docker-compose exec php composer install
```

```console
foo@bar: laravel-blog $ docker-compose exec php php artisan key:generate
```

```console
foo@bar: laravel-blog $ docker-compose exec php npm install
foo@bar: laravel-blog $ docker-compose exec php npm run production
```

## Status
Project is: _in progress_

## Contact
Created by [@stonedch](https://github.com/stonedch)

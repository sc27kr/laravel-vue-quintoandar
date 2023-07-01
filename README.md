# QuintoAndar Clone

A QuintoAndar Clone built with Laravel and Vue.js.

## Getting started

### Prerequisites
```bash
docker -v
docker-compose -v
```

### Installing

Clone this repo.

```bash
git clone https://github.com/sc27kr/laravel-vue-quintoandar.git
```

Copy .env.

```bash
cd laravel-vue-quintoandar
cp .env.example .env
```

Install the project dependencies.

```bash
composer i
npm i
```

Create and start containers.

```bash
docker-compose up --build
```

Create database and migrate.

[localhost:8080](http://localhost:8080)

```bash
php artisan migrate --seed
```

Set the application key.

```bash
php artisan key:generate
```

Serve the application.

```bash
php artisan serve
npm run dev
```

Register and verify your account.

* [localhost:8000](http://localhost:8000)
* [MailHog](http://localhost:8025)

Enjoy!

## Built with

* PHP
* Laravel
* Vue.js
* Inertia.js
* Tailwind CSS

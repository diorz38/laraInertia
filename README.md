Laravel+Inertia+Vue3
<img src="https://raw.githubusercontent.com/diorz38/laraInertia/af56b1847573738211b22b3f6407c7e1511204fd/screenshoots/ss1.png?token=ABF4DVNH35BLGVFA42Y275LBWYLHU" alt="Users Page">

## Installation

Clone the repo locally:

```sh
git clone https://github.com/diorz38/laraInertia.git
cd laraInertia
```

Install PHP dependencies:

```sh
composer install
```

Install NPM dependencies:
Build assets:

```sh
npm run dev
```

Setup configuration:

```sh
cp .env.example .env
```

Generate application key:

```sh
php artisan key:generate
```

Create an SQLite database. You can also use another database (MySQL, Postgres), simply update your configuration accordingly.

```sh
touch database/database.sqlite
```

Run database migrations:

```sh
php artisan migrate
```

Run database seeder:

```sh
php artisan db:seed
```

Run the dev server (the output will give the address):

```sh
php artisan serve
```
You're ready to go! and login with:

- **Username:** johndoe@example.com
- **Password:** passw0rd

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

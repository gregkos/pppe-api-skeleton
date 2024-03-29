## A starting point

This is intended to be an all in one starting point to develop new APIs using a modern stack.

### Stack

- [Laravel](https://laravel.com) as the framework
- [Pint](https://laravel.com/docs/pint) for code style
- [Pest](https://pestphp.com) for testing
- [PHPStan](https://phpstan.org) and [Larastan](https://github.com/nunomaduro/larastan) for static analysis

### Prerequisites

This is intended to be run with [Valet](https://laravel.com/docs/valet). However, as with any standard Laravel installation, [Sail](https://laravel.com/docs/sail) is included, should you prefer a containerized approach.

- PHP 8.2+ (Created using 8.2)
- Node.js 18+ with npm
- Composer 2+

### Installation

- Clone the repo
- Run `composer install`
- Copy over the `.env.example` file and populate as needed
- Run `php artisan key:generate` to generate a unique key
- Initialize the database with `php artisan migrate`
- Use `./vendor/bin/pint`, `./vendor/bin/phpstan`, and `./vendor/bin/pest` as needed

# Blog CMS

Blog system with comments and categories.

## Requirements

- PHP **>= 7.2.0**
- BCMath PHP Extension
- Ctype PHP Extension
- JSON PHP Extension
- Mbstring PHP Extension
- OpenSSL PHP Extension
- PDO PHP Extension
- Tokenizer PHP Extension
- XML PHP Extension
- Composer

## Development

- Clone repository.
- Run `composer install` command.
- Create `MySQL database` and login credentials to it.
- Run `cp .env.example .env` command.
- Run `php artisan key:generate` command.
- Fill database credentials on `.env` file.
- Run `php artisan migrate` command.
- Run `php artisan storage:link` command.

P.S.: if you dont use virtual machine, run `php artisan serve` command.

## Deploy

- For first user run `php artisan user:create` command.
- For images upload run `php artisan storage:link` command.

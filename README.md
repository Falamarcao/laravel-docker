# Laravel Docker

```sh
    docker compose run --rm --build composer create-project --prefer-dist laravel/laravel .

    docker compose up -d --build server

    docker compose run --rm artisan migrate

    docker compose run --rm npm install
```
# Laravel Docker

```sh
    docker compose run --rm --build composer create-project --prefer-dist laravel/laravel .
    sudo chmod -R 777 ./src/storage/

    docker compose up -d --build server

    docker compose run --rm artisan migrate

    docker compose run --rm npm install
```
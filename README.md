# API

The microservice was built using [Lumen](https://lumen.laravel.com/docs), which is essentially a lighter version of Laravel.

I chose Lumen for its scalability benefits. Unlike Laravel, which comes with many built-in dependencies, Lumen is more lightweight and consumes fewer resources, making it easier to scale efficiently.

## First Run

First copy .env-sample and create a .env file

```
docker-compose build
php artisan migrate
php artisan db:seed
```

## Running

```
docker-compose up
```

# Try

```
curl --location --request GET 'localhost:8080/movies/autocomplete?search=""'
```

# Front end

On the front end, I built a simple infrastructure using React. here you can see the files and directories:

- src
  - actions : Actions are a concept of classes that handle requests to the backend.
  - components: Generic components used throughout the entire system.
  - pages : Pages of your website
  - utils : Utility functions and helpers.
- vite.config.ts : This file configures Vite. Vite is lighter than using react-scripts.
- .env-sample : A sample .env file.
- .prettierrc : This file determines the formatting rules for your code.

## HOW TO START

First copy .env-sample and create a .env file

```
npm install
npm run start
```

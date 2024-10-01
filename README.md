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

# Front end

On the front end, I built a simple infrastructure using React. here you can see the files and directories:

- src
  - actions : Actions is a concept of classes that make request with the backend
  - components: Generic components to entire system
  - pages : Pages of your website
  - utils : Utils library
- vite.config.ts : this is a file to configure vite, vite is more ligther than use react-scripts
- .env-sample : this is a sample of .env file
- .prettierrc : this file determine all the formatation of yours code lines.

## HOW TO START

First copy .env-sample and create a .env file

```
npm install
npm run start
```

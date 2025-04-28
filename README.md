# Errorfix - Laravel Workshop

This project is part of the [Monitor and Debug Laravel Applications with Sentry](https://sentry.io/resources/debug-laravel-with-sentry/) Workshop.

## Getting started

You'll need PHP (8.1+), Composer, and Node.js installed. To run the project:

1. `composer install` and `npm install` to install dependencies
2. `npm run build` to build frontend assets
3. `touch database/database.sqlite` to create the database file
4. `php artisan migrate:fresh` to setup the database tables
5. `php artisan db:seed` to populate the database with demo data
6. `composer dev:ssr` to boot up the app in SSR mode

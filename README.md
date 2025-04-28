# Errorfix - Laravel Workshop

This project is part of the [Monitor and Debug Laravel Applications with Sentry](https://sentry.io/resources/debug-laravel-with-sentry/) Workshop.

## Getting started

You'll need PHP (8.1+), Composer, and Node.js installed. To run the project:

```bash
composer install                 # to install PHP dependencies
npm install                      # to instal Node dependencies
npm run build                    # to build frontend assets
touch database/database.sqlite   # to create the local database file
php artisan migrate:fresh        # to apply migrations to the database
php artisan db:seed              # to seed the database with demo data
cp .env.example .env             # to setup env variables
php artisan key:generate         # to generate an application key
composer dev:ssr                 # to start the project in SSR mode
```

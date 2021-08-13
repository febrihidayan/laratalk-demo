# Laratalk Demo
Laratalk demo package and Breeze for authentication using Laravel 8.

### Quick start
You can run this command in terminal.

```bash
composer create-project febrihidayan/laratalk-demo example-app
```

Then follow this in order:

1. `cp .env.example .env`
2. `php artisan key:generate`
3. Do database configuration and create pusher account
4. `php artisan migrate`
5. `yarn && yarn watch` or `npm install && npm run watch`
6. `php artisan storage:link`
7. `php artisan serve`
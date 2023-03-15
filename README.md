# laravel-react-install - Version 10.3.3

## Requirements
- Composer installed and up-to-date
- MySQL (or other), running

## Installation

1. Install laravel in a new project `{project-name}`
```
composer create-project laravel/laravel {project-name}
```

2. Install Breeze (containing login system, user table, registration...)
```
composer require laravel/breeze --dev

php artisan breeze:install react
npm install
npm run dev
```
> Note : Keep the previous console running, and open a new terminal to continue

3. Fill the `.env` file with the DB information
```
APP_NAME="project-name"
...

...
DB_DATABASE=project-name
DB_USERNAME=root
DB_PASSWORD=
...
```

4. Run the migration
```
php artisan migrate
```

5. Run the server
```
php artisan serve
```
> Note : Keep the previous console running

6. You are all set! Now, Happy coding!

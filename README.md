# Laravel 8 Breeze Implementation
 In this project, here i implement laravel breeze. 
 And also here i show that step by step how to integrate laravel breeze.
 
 Laravel Breeze is a minimal, simple implementation of all of Laravel's authentication features, including login, registration, password reset, email verification, and password confirmation.

## How to Integrate Laravel Breeze
##### 1. Create new laravel project via composer
```
composer create-project laravel/laravel laravelBreezeApp
```

Go to project directory ```cd laravelBreezeApp``` or open project with IDE.

##### 2. Install laravel 8 breeze package
```
composer require laravel/breeze:1.9.2
```

##### 3. After installed the Laravel Breeze package, run the Artisan command
```
php artisan breeze:install
npm install
npm run dev
```

##### 4. Create a new database
Here I'm using my MySQL PHPMyAdmin to create a database.<br>
Open ``` .env ``` file and add your database credentials.
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel_breeze
DB_USERNAME=root
DB_PASSWORD=
```
Run migration artisan command
```
php artisan migrate
```

Then run  ```php artisan serve``` & you can see the project on ```http://127.0.0.1:8000```
###### Completed.

Laravel Official Documentation: https://laravel.com/docs/8.x/starter-kits

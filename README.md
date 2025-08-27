# Laravel CRM Clone

A simple **CRM Lite** built with Laravel 9 (PHP 8.0).  
Features:
- User authentication (Laravel Breeze)
- Customer management (CRUD)
- RESTful API
- SQLite/MySQL support

## Setup
```bash
git clone https://github.com/alokpandey78/laravel-crm-clone.git
cd laravel-crm-clone/src
composer install
npm install && npm run build
cp .env.example .env
php artisan migrate
php artisan serve

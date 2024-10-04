### 2fa Authorisation with Auth Mobile App

> https://laracoding.com/google-authenticator-for-2fa-in-laravel/

## Step 1: Install Laravel

> composer create-project --prefer-dist laravel/laravel laravel-google-2fa

> cd laravel-google-2fa

## Step 2: Install Google Authenticator on Your Phone

## Step 3: Install Jetstream

> composer require laravel/jetstream
> php artisan jetstream:install livewire

## Step 4: Run Migrations

> php artisan migrate

## Step 5: Enable Two-Factor Authentication

> User Model

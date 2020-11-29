## Installation
Install required packages
```bash
composer install
```

Setup environment configuration and update it accordingly (db, app key etc)
```bash
cp .env.example .env
```

Migrate DB and seeder
```bash
php artisan migrate:fresh --seed
```
> Set the db config before run miration

## Packages includes
- [Data Transfer Object](https://github.com/spatie/data-transfer-object) - Structure "unstructured data", which is normally stored in associative arrays.
- [Eloquent Filter](https://github.com/Tucker-Eric/EloquentFilter) - An Eloquent way to filter Eloquent Models and their relationships.
- [Eloquent Sluggable](https://github.com/cviebrock/eloquent-sluggable) - Easy creation of slugs for your Eloquent models in Laravel.
- [Laravel Enum](https://github.com/BenSampo/laravel-enum) - Simple, extensible and powerful enumeration implementation for Laravel.
- [Lumen Passport](https://github.com/dusterio/lumen-passport) - Making Laravel Passport work with Lumen
- [Laravel Permission](https://github.com/spatie/laravel-permission) - Allows you to manage user permissions and roles in a database.
- [Laravel API Response](https://github.com/raditzfarhan/laravel-api-response) - Laravel and Lumen API response transformer/formatter.
- [Laravel Socialite](https://github.com/laravel/socialite) - Provides an expressive, fluent interface to OAuth authentication with Facebook.
- [Lumen Action](https://github.com/laraditz/action) - Single action class for Laravel and Lumen to keep your application DRY.
- [Lumen Command Generator](https://github.com/raditzfarhan/lumen-command-generator) - Includes some of the missing Laravel artisan command into Lumen.
- [Faker Provider](https://github.com/mbezhanov/faker-provider-collection) - Faker provider for Commerce and etc.

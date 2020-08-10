#### Authentication Quickstart

```php
composer require laravel/ui

php artisan ui vue --auth


```php
php artisan migrate      
```

##### Email Log

```php
// if error 
php artisan config:cache // log storage /log
// restart server
```

#### Syn

```javascript
if(mix.inProduction()) {
	mix.version();
}

mix.browserSync('http://localhost:8000/');
```

#### Make Model

```phph
php artisan make:model Category -mr
php artisan migrate
```


#### Make Seeder

```php
php artisan make:seeder CategoriesTableSeeder
php artisandb:seed
```

#### Policy

```php
php artisan make:policy CategoryPolicy --model=Category
```
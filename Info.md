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
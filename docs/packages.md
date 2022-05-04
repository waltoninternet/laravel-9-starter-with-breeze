# [Applicaion Docs Index](index.md)

## Installed Packages


#### *development only*

- [barryvdh/laravel-debugbar](https://github.com/barryvdh/laravel-debugbar)

```
composer require barryvdh/laravel-debugbar --dev

php artisan vendor:publish --provider="Barryvdh\Debugbar\ServiceProvider"

### .env
DEBUGBAR_ENABLED=true

```

- [laravel/telescope](https://laravel.com/docs/8.x/telescope)
```
composer require laravel/telescope

php artisan telescope:install

php artisan migrate

```


- [spatie/laravel-ray](https://spatie.be/docs/ray/)
```
composer require spatie/laravel-ray  --dev

php artisan ray:publish-config

## in code
ray('My first ray call') or dd() or dump()

```


#### *for application*
- [laravel/breeze](https://laravel.com/docs/starter-kits#laravel-breeze)
```
composer require laravel/breeze --dev

php artisan breeze:install

npm install

npm run dev

php artisan migrate
```
# Trash Panda

## 1. Development

### 1. Initial Creation

`composer create-project --prefer-dist laravel/laravel trash-box`
`

### 1. Continued Active Development

`php artisan serve`
`php artisan test`
`php artisan config:clear`
`php artisan cache:clear`

### 1. Returning Development After a Long Time

```shell
composer upgrade
php artisan migrate:fresh
php artisan clear-compiled
php artisan route:clear
php artisan config:clear
```

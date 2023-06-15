# laravel_docker

# Installation
#### 1.Clone laravel in empty folder
```javascript
composer create-project laravel/laravel myproject-app
```
```javascript
cd myproject-app
```
Copy all clone to this folder.
#### 2.Setting Username&Password Database (docker-compose.yml&.env.dev)

#### 3.Build
```javascript
docker compose build
```

#### 4.Run
```javascript
docker compose up -d
```
#### 5.Run container bash
```javascript
docker compose exec -it app bash
```
#### 6.migrate table to Database
```javascript
php artisan migrate
```

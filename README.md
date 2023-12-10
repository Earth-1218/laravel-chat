
# Laravel Whatsapp Clone

![alt text](https://github.com/Earth-1218/laravel-chat/blob/main/whatsapp.png?raw=true)

### Installation (guide to run the application in local environment)

- clone or fork this project
```
git clone https://github.com/Earth-1218/laravel-chat.git
```

- then copy .env from .env.example and configure it
```
cp .env.example .env
```

- at this step you need to configure your database name, and pusher creds, but i already fill it with dummy test.

- install dependency
```
composer install
```

```
npm install
```

- generate key and then run migration & seeder
```
php artisan key:generate
```

```
php artisan migrate:fresh --seed
```

- asset build development
```
npm run dev
```
- asset build deployment
```
npm run build
```

- serve **to run websocket (terminal 1)**
```

php artisan websockets:serve
```

- serve **to run server (terminal 2)**
```
php artisan serve
```

### Author
**Ravi Majithiya**


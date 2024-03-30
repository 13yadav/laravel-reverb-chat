# Chat Application

Built using Laravel 11 + Reverb + React.js

## Installation

Clone and install dependendies

```bash
  git clone https://github.com/13yadav/laravel-reverb-chat.git
  cd laravel-reverb-chat
  composer install
  npm install
```

Build frontend assets:

```bash
npm run build
# or run below for dev server
npm run dev
```

Start listening to the Laravel events:

```bash
php artisan queue:listen
```

Start the WebSocket server:

```bash
php artisan reverb:start
```

Start the server:

```bash
php artisan serve
```

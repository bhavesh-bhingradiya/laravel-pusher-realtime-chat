# Laravel Vue 3 Single Page Application - Dynamic Chat Experience

Explore this cutting-edge real-time chat application, meticulously crafted using Laravel and Vue 3 technologies.

## Preparatory Steps

Before diving into the project, ensure you fulfill the following prerequisites:

- [Node.js](https://nodejs.org/) installation
- [Composer](https://getcomposer.org/) installed
- [Laravel](https://laravel.com/) setup
- [Vue CLI](https://cli.vuejs.org/) installed

## Project Initialization

Embark on a seamless setup and execution process by adhering to the following steps:

1. **PHP Dependencies Installation:**

    ```bash
    composer install
    ```

2. **JavaScript Dependencies Installation:**

    ```bash
    npm install
    ```

3. **Create a Duplicate of the `.env` File:**

    ```bash
    cp .env.example .env
    ```

4. **Generate the Application Key:**

    ```bash
    php artisan key:generate
    ```

5. **Update Your `.env` File:**

    - Configure the required database information.
    - Integrate Pusher credentials.
    - Set `BROADCAST_DRIVER` to Pusher.

6. **Execute Database Migrations and Seeders:**

    ```bash
    php artisan migrate --seed
    ```

## Developmental Phase

Initiate the development server with the following command:

```bash
npm run dev & php artisan serve
```

Your Laravel Vue 3 Single Page Application is now primed for development. Access it via [http://localhost:8000](http://localhost:8000) and relish the immersive real-time chat functionality.

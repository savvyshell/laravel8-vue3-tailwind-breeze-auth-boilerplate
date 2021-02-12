# laravel8-vue3-tailwind-breeze-auth-boilerplate

 Preconfigured with Laravel 8, Vue 3, Tailwind CSS & Breeze (Auth)
 
 To get started:

    git clone https://github.com/savvyshell/laravel8-vue3-tailwind-breeze-auth-boilerplate.git
    cd laravel8-vue3-tailwind-breeze-auth-boilerplate
    composer install
    npm install

Initialize:

* Create .env file (from .env.example)

Then run:

    php artisan key:generate
    
Followed by:

    php artisan cache:clear
    
    php artisan config:clear

If any npm run dev issues encountered, follow these steps:

    rm -rf node_modules
    rm package-lock.json yarn.lock
    npm cache clear --force
    npm install

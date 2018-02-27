#Install

    git clone git@github.com:bahek2462774/laraveltestapi.git
    composer install
    cp .env.example .env
    Edit your .env file
    php artisan key:generate
    php artisan migrate --seed
    php artisan passport:install
    php artisan storage:link
    yarn 
    yarn prod

#Run server
(http://127.0.0.1:8000)  

    php artisan serve
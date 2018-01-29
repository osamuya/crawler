# Setup

## get Composer & goutte
````
cd /PROJECT_DIR
php -r "readfile('https://getcomposer.org/installer');" > composer-setup.php
php composer-setup.php create-project laravel/laravel gate --prefer-dist
php composer.phar require fabpot/goutte
````


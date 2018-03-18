# laravel-docker
Laravel 5.6 with Laradock(docker)
# Objective
To help developer speed up the setup progress on their local machine
# Installation
1. ```git clone https://github.com/pangminfu/laravel-docker.git```
2. ```cd laravel-docker```
3. ```git submodule init```
4. ```git submodule update```
5. Create symlink for laradock env file point to ```/config/laradock/.env```
    - ```cd laradock```
    - ```ln -s ../config/laradock/.env .env```
6. Create symlink for laravel env file point to ```/config/laravel/.env```
    - ```cd ../laravel```
    - ```ln -s ../config/laravel/.env .env```
7. Install all Laravel framework dependency
    - ```composer install```
8. Generate Laravel encryption key
    - ```php artisan key:generate```
    
# Start Laradock(docker)
1. ```cd laradock```
2. Start up apache, mysql, redis and phpmyadmin with docker. you may pass in different option to start up different container
    - ```docker-compose up -d apache2 mysql redis phpmyadmin```
3. Subsequently you may start up the container by calling :
    - ```docker-compose start```
    
# Laravel documentation
Please refer to https://laravel.com/docs/5.6/installation

# Laradock Documentation
Please refer to http://laradock.io/

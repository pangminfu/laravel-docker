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
    - ```ln -s ../config/laradock/.env .env```
6. Create symlink for laravel env file point to ```/config/laravel/.env```
    - ```ln -s ../config/laravel/.env .env```

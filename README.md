# laravel-docker
Laravel 5.6 with Laradock(docker)
# Objective
To help developer speed up the setup progress on their local machine
# Installation
1. ```git clone https://github.com/pangminfu/laravel-docker.git```
2. ```cd laravel-docker```
3. ```./setup.dev```
    
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

# laravel + docker configuration
Minimal docker laravel with nginx and php-fpm without bd

Clone: git clone https://github.com/codesshaman/minimal_docker_laravel_nginx_php.git

RUN:

cd minimal_docker_laravel_nginx_php

unzip laravel.zip

sudo docker-compose up -d --build

Connect:

http://localhost:8080/

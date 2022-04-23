# laravel + docker configuration
Minimal docker laravel with nginx and php-fpm without bd

Your need docker and docker-compose in your operation system.

Clone: git clone https://github.com/codesshaman/minimal_docker_laravel_nginx_php.git

GO TO FOLDER:
cd minimal_docker_laravel_nginx_php

UNZIP:
unzip laravel.zip

BUILD (first start):
docker-compose up -d --build

RUN:
docker-compose up -d

STOP:
docker-compose down

CONNECT:
docker exec -it nginx_laravel sh

OPEN:
http://localhost/

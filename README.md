Docker Nginx 1.15 & PHP-fpm 7.2 on Alpine Linux 3.7
==============================================
Nginx 1.15 & PHP-FPM 7.2 setup for Docker, build on [Alpine Linux](http://www.alpinelinux.org/).

[![Docker Pulls](https://img.shields.io/docker/pulls/coskunsoysal/alpine3.7-nginx-php7.svg)](https://hub.docker.com/r/coskunsoysal/alpine3.7-nginx-php7/)

This image runs with common php extensions:
>>   php7-fpm php7-mysqli php7-json php7-openssl php7-curl 
>>   php7-zlib php7-xml php7-phar php7-intl php7-dom php7-xmlreader php7-ctype 
>>   php7-mbstring php7-gd curl

nginx and php services controlled by supervisor


Usage
-----
Start the Docker containers:

    docker run -p 80:80 coskunsoysal/alpine3.7-nginx-php7

See the PHP info on http://localhost ( http://0.0.0.0:80 )

Enjoy

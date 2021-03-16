FROM php:7.4-fpm-alpine

RUN sed -i 's/dl-cdn.alpinelinux.org/mirrors.aliyun.com/g' /etc/apk/repositories

WORKDIR /var/www

RUN docker-php-ext-install pdo pdo_mysql
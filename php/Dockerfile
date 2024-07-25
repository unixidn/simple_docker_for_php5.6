FROM php:5.6-fpm-alpine

RUN docker-php-ext-install pdo pdo_mysql mysql mysqli


ADD conf.d/php.ini /usr/local/etc/php/conf.d/php.ini

WORKDIR /var/www






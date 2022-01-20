FROM php:5.6-apache
RUN apt-get update && docker-php-ext-install mysql mysqli pdo_mysql mbstring && a2enmod rewrite

COPY ./php.ini /usr/local/etc/php/

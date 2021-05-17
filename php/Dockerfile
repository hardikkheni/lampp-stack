FROM php:7.4-apache

RUN docker-php-ext-install pdo_mysql && \
    apt update && \
    apt install -y zip unzip

RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer
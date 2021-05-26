FROM php:7.4-apache

RUN docker-php-ext-install mysqli pdo pdo_mysql  &&  docker-php-ext-enable pdo_mysql && \
    apt update && \
    apt install -y zip unzip

RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer
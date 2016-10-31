FROM php:7.0-apache

RUN apt-get update \
    && apt-get install vim libmcrypt-dev -y \
    && docker-php-ext-install mysqli pdo pdo_mysql mcrypt

RUN a2enmod rewrite
RUN usermod -u 1000 www-data \
    && groupmod -g 1000 www-data

COPY ./docker-php.conf /etc/apache2/conf-enabled/docker-php.conf
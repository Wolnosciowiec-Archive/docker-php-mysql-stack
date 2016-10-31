# docker-php-mysql-stack

[![Build Status](https://travis-ci.org/Wolnosciowiec/docker-php-mysql-stack.svg?branch=master)](https://travis-ci.org/Wolnosciowiec/docker-php-mysql-stack)

Simple developer environment that includes PHP, MySQL and phpMyAdmin.
By default includes a PHP 5.6 that I used to work with legacy code, but easily PHP 7 could be run in this configuration.

# Usage

Clone this repository inside of you'r project's directory, and run `sudo docker-compose up --force-recreate --build`
in one of suites directory

# Forwarded ports
- Database administration: localhost:8003
- PHP7: localhost:8005
- PHP5.6: localhost:8002
FROM phpdockerio/php7-cli

RUN set -x && apt-get update && apt-get install git php7.0-mysql -y

WORKDIR /var/www
CMD "php -S 0.0.0.0:8001 -t /var/www"
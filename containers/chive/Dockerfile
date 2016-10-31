FROM phpdockerio/php7-cli

RUN set -x && apt-get update && apt-get install git php7.0-mysql -y
RUN git clone https://github.com/fusonic/chive /app

EXPOSE 8003 8003

WORKDIR /app
CMD /usr/bin/php7.0 -S 0.0.0.0:8003 -t /app -c /app/php.ini
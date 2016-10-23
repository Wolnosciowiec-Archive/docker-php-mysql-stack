FROM gilbitron/php5.6-mysql

RUN apt-get update # you can modify the comment here everytime you add a new extension, this will skip the cache for apt-get update

# Install additional PHP 5.6 extensions
RUN apt-get install -y --allow-unauthenticated php5.6-apcu php5.6-mbstring

WORKDIR /app
CMD ["./run.sh"]

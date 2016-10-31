FROM gilbitron/php5.6-mysql

RUN apt-get update && \
    apt-get install -y --allow-unauthenticated php5.6-apcu php5.6-mbstring

WORKDIR /app
CMD ["./run.sh"]

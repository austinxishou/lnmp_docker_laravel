FROM php:7.1-cli

COPY ./composer.phar /usr/local/bin/composer
RUN apt-get update && apt-get install -y git \
    && chmod 755 /usr/local/bin/composer
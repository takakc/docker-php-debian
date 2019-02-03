FROM php:7.3.1-fpm-stretch
MAINTAINER kan


RUN apt-get update && apt-get install -y \
  vim \
  wget

RUN docker-php-ext-install pdo_mysql mysqli

RUN curl -sS https://getcomposer.org/installer | php && \
    mv composer.phar /usr/local/bin/composer

WORKDIR /var/www

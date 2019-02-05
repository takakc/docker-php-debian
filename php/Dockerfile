FROM php:7.2.0-fpm-stretch
MAINTAINER kan


RUN apt-get update && apt-get install -y \
  unzip \
  vim \
  wget \
  zip \
  zlib1g-dev

# Root User execution compoesr
ENV COMPOSER_ALLOW_SUPERUSER 1
ENV COMPOSER_NO_INTERACTION 1

RUN docker-php-ext-install \
  zip \
  mysqli \
  pdo_mysql

RUN curl -sS https://getcomposer.org/installer | php && \
    mv composer.phar /usr/local/bin/composer

WORKDIR /var/www

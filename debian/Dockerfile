FROM debian:9
MAINTAINER kankan
ARG username="kan"
ARG password="kankan"


RUN apt-get update && apt-get install -y \
  git \
  vim

# .php or .html put this directory
RUN mkdir /var/www && mkdir /var/www/html

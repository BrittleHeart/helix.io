FROM php:8.1-fpm-apline

WORKDIR /var/www

RUN apt update -y && apt upgrade -y
RUN apt install -y \
  build-essential \ 
  vim \
  wget \ 
  curl \
  libpng \
  postgresql \
  postgresql-client \
  zsh \
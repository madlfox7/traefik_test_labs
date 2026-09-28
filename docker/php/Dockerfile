FROM php:8.4-fpm-alpine as base
RUN apk add --no-cache $PHPIZE_DEPS linux-headers
RUN docker-php-ext-install pdo_mysql mysqli opcache
WORKDIR /app
EXPOSE 9000
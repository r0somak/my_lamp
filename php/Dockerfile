FROM php:7.3-rc-fpm-alpine
RUN apk update; \
apk upgrade;
RUN docker-php-ext-install mysqli
COPY php.ini /usr/local/etc/php/php.ini

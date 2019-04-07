FROM php:7.3.4-fpm-alpine3.9

RUN apk add composer \
    && apk add --no-cache icu-dev
RUN docker-php-ext-configure intl --enable-intl \
    && docker-php-ext-install intl \
    && docker-php-ext-install mysqli pdo pdo_mysql


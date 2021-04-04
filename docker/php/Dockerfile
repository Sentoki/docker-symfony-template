FROM php:8.0-fpm

RUN pecl install xdebug-3.0.3 \
    && docker-php-ext-enable xdebug

COPY xdebug.ini /usr/local/etc/php/conf.d/docker-php-ext-xdebug.ini
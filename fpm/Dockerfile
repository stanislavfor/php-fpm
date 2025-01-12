FROM php:8.4-fpm

# Установка зависимостей и расширений
RUN apt-get update && apt-get install -y \
    libmemcached-dev \
    zlib1g-dev \
    && pecl install memcache \
    && docker-php-ext-enable memcache \
    && docker-php-ext-install pdo_mysql

# Копирование файла php.ini
COPY php.ini /usr/local/etc/php/


# FROM php:8.4-fpm
# COPY php.ini /usr/local/etc/php/

FROM php:7.3-fpm

RUN apt-get update -y \
	&& docker-php-ext-install mysqli pdo_mysql \
	&& docker-php-ext-enable mysqli \
	&& docker-php-ext-enable pdo_mysql


COPY ./my-php.ini /usr/local/etc/php/php.ini

EXPOSE 9000

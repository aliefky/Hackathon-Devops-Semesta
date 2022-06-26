FROM php:7.4-apache

RUN apt-get -y update --fix-missing
RUN apt-get upgrade -y

WORKDIR /var/www/html/semesta
ADD . /var/www/html/
RUN chown -R www-data:www-data /var/www/html/semesta

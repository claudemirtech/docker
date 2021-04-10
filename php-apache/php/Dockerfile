FROM php:7.4-apache
WORKDIR /var/www/html
RUN docker-php-ext-install mysqli
RUN a2enmod rewrite && \
    service apache2 restart
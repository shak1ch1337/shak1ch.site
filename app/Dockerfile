FROM php:8.2-apache
COPY . /var/www/html
WORKDIR /var/www/html
EXPOSE 80


RUN ["chmod", "-R", "777", "/var/www/html"]
RUN ["chown", "-R", "www-data", "/etc/apache2/sites-available/000-default.conf"]
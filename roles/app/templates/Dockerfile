FROM php:fpm

# Устанавливаем необходимые расширения PHP
RUN docker-php-ext-install pdo pdo_mysql mysqli

# Копируем приложение в контейнер
COPY . /var/www/html

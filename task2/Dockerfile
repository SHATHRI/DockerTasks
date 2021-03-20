FROM php:7.2-cli

EXPOSE 8000
RUN mkdir /app
COPY index.php /app
WORKDIR /app
CMD ["php", "-s", "0.0.0.0:8000"]
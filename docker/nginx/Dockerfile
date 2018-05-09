FROM nginx:stable-alpine

RUN  mkdir -p /var/www/html/www/drupal \
  && addgroup -g 82 -S www-data \
  && adduser -u 82 -D -S -G www-data www-data \
  && chown -R www-data:www-data /var/www/html/www/drupal
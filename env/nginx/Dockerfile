FROM nginx:alpine
ADD nginx.conf /etc/nginx/
ARG PHP_UPSTREAM=php-fpm
ENV NAME World
RUN adduser -D -H -u 1000 -s /bin/bash www-data
RUN rm /etc/nginx/conf.d/default.conf
CMD ["nginx"]
EXPOSE 80 443

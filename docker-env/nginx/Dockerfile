FROM nginx:alpine
ADD nginx.conf /etc/nginx/
RUN adduser -D -H -u 1000 -s /bin/bash www-data
RUN rm /etc/nginx/conf.d/default.conf
CMD ["nginx"]
EXPOSE 80 443

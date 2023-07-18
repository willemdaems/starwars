FROM nginx:1.24.0-alpine

RUN apk add vim
COPY --chown=nginx:nginx ./docker/nginx/config/nginx.conf /etc/nginx/nginx.conf

RUN mkdir /var/www
COPY ./docker/nginx/files/index.html /var/www

EXPOSE 80

FROM nginx:1.19.8-alpine

LABEL org.opencontainers.image.source=https://github.com/manugorre/cestnotreprojet.fr

COPY ./nginx/nginx.conf /etc/nginx/conf.d/default.conf
COPY /www /usr/share/nginx/html
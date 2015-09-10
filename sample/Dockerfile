# Version: 0.0.1
FROM ubuntu:14.04
MAINTAINER xubai
ENV REFRESHED_AT 2015-09-09
RUN apt-get update
RUN apt-get install -y -q nginx
RUN mkdir -p /var/www/html
ADD nginx/global.conf /etc/nginx/conf.d/
ADD nginx/nginx.conf /etc/nginx/nginx/conf
EXPOSE 80

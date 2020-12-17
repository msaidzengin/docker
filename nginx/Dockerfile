FROM ubuntu:latest

LABEL maintainer="<msaidzengin@gmail.com>"

RUN apt-get update

RUN apt-get install -y nginx

ADD [ "./index.html", "/var/www/html/" ]

EXPOSE 80

ENTRYPOINT nginx -g 'daemon off;'

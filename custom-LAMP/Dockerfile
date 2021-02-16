FROM ubuntu
MAINTAINER Venkat
RUN apt-get update; apt-get install -y apache2 mysql-server php
CMD google.com
COPY custom-index-fid.html /var/www/html/index.html
LABEL env PROD, app FIDAPP
VOLUME /var/www/html
ENTRYPOINT ping -c 10

FROM ubuntu
MAINTAINER Venkat
RUN apt-get update; apt-get install nginx -y
RUN apt-get update; apt-get install curl -y
EXPOSE 80
COPY custom-nginx/custom-index-fid.html /var/www/html/index.html
CMD nginx -g "daemon off;"

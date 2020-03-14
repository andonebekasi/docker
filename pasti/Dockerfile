FROM ubuntu
RUN apt-get update
RUN apt-get install nginx -y
COPY index.html /var/www/html/
COPY image001.jpg /var/www/html/
COPY image003.jpg /var/www/html/
EXPOSE 80
CMD ["nginx","-g","daemon off;"]

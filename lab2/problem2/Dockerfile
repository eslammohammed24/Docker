FROM httpd:latest
COPY ./file.html /usr/local/apache2/htdocs/
COPY ./httpd.conf /usr/local/apache2/conf/httpd.conf
EXPOSE 9999
ENV CONTAINER docker
CMD echo $CONTAINER && httpd -D FOREGROUND


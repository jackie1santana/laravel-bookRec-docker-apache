FROM httpd

RUN apt-get update 

COPY httpd.conf /usr/local/apache2/conf/httpd.conf


CMD ["httpd", "-D", "FOREGROUND"]
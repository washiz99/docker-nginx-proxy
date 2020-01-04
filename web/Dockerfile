FROM httpd:2.4.41

WORKDIR /usr/local/apache2/htdocs

COPY ./conf/httpd.conf /usr/local/apache2/conf/httpd.conf
COPY ./conf/extra/httpd-vhosts.conf /usr/local/apache2/conf/extra/httpd-vhosts.conf
COPY ./htdocs/ /usr/local/apache2/htdocs/

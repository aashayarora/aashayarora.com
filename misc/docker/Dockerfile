FROM httpd:alpine

ADD ./conf/httpd.conf /usr/local/apache2/conf
ADD ./conf/httpd-ssl.conf /usr/local/apache2/conf/extra

ADD ./src/ /usr/local/apache2/htdocs/

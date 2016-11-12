FROM qafe/proxy-httpd

MAINTAINER qafe

COPY ./httpd-banq-proxy.conf /usr/local/apache2/conf/extra/
RUN echo "Include conf/extra/httpd-banq-proxy.conf" >> /usr/local/apache2/conf/httpd.conf

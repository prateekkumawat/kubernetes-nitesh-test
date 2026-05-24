FROM redhat/ubi10:latest 

RUN yum install httpd -y 

RUN mkdir /var/www/web

RUN mkdir /var/www/virtual

CMD ["/usr/sbin/httpd", "-D", "FOREGROUND" ]
FROM centos:latest
MAINTAINER pepelepu
RUN yum -y install httpd; mkdir /opt/shared
COPY index.html /var/www/html/
CMD [“/usr/sbin/httpd”, “-D”, “FOREGROUND”]
EXPOSE 80

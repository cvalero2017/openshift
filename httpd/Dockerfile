FROM centos:latest
MAINTAINER pepelepu
RUN yum -y install httpd; mkdir /opt/shared
COPY index.html /var/www/html/
RUN systemctl enable httpd.service

EXPOSE 80

CMD ["/usr/sbin/init"]

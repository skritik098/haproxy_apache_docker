FROM registry.access.redhat.com/ubi8/ubi:latest

RUN yum repolist && yum install httpd -y && yum clean all

ENV DOCROOT  /var/www/html

COPY src/*  ${DOCROOT}/

EXPOSE 80

RUN rm -rf /run/httpd && mkdir /run/httpd

CMD /usr/sbin/httpd -DFOREGROUND 

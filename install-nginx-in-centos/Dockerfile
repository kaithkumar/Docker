# FROM centos:latest
FROM debian:latest
RUN yum install -y httpd

EXPOSE 80

CMD ["httpd", "-D", "FOREGROUND"]
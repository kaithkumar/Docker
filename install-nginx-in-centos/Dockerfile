FROM centos:latest

RUN yum update & yum install -y httpd

EXPOSE 80

CMD ["httpd", "-D", "FOREGROUND"]
FROM centos:latest

ENV LANG en_US.UTF-8

# Update the system and install necessary packages
RUN yum update -y && \
    yum install -y httpd && \
    yum clean all
    
RUN yum install -y httpd

EXPOSE 80

CMD ["httpd", "-D", "FOREGROUND"]
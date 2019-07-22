FROM ubuntu
MAINTAINER jyothi
RUN apt-get update
RUN apt-get install -y apache2
EXPOSE 80
RUN systemctl start tomcat
RUN systemctl status tomcat

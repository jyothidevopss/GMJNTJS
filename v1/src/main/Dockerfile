FROM ubuntu:latest
MAINTAINER jyothi
RUN apt-get -y update
RUN mkdir /usr/local/tomcat
CMD wget wget http://www-eu.apache.org/dist/tomcat/tomcat-9/v9.0.14/bin/apache-tomcat-9.0.14.tar.gz -P /tmp
RUN tar xf /tmp/apache-tomcat-9*.tar.gz -C /opt/tomcat
EXPOSE 8085
CMD systemctl start tomcat

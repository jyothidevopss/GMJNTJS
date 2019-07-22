FROM ubuntu
MAINTAINER jyothi
RUN apt-get update
RUN apt-get install -y apache2
EXPOSE 80
RUN sudo systemctl start tomcat
RUN sudo systemctl status tomcat

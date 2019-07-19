FROM ubuntu:latest
RUN apt-get -y update && apt-get -y upgrade
RUN mkdir /usr/local/tomcat
RUN wget https://www-eu.apache.org/dist/tomcat/tomcat-9/v9.0.22/bin/apache-tomcat-9.0.22.tar.gz
RUN cd /tmp && tar xvfz tomcat.tar.gz
RUN cp -Rv /tmp/apache-tomcat-8.5.16/* /usr/local/tomcat/
EXPOSE 8085
CMD /usr/local/tomcat/bin/catalina.sh run

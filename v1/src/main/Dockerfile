FROM ubuntu
RUN wget http://www-eu.apache.org/dist/tomcat/tomcat-9/v9.0.0.M17/bin/apache-tomcat-9.0.0.M17.tar.gz
RUN tar -zxpvf apache-tomcat-9.0.0.M17.tar.gz -C /opt/
RUN cd /opt/
RUN mv apache-tomcat-9.0.0.M17.tar.gz tomcat
RUN echo "export CATALINA_HOME='/opt/tomcat/'" >> ~/.bashrc
RUN source ~/.bashrc
CMD cd /opt/tomcat/bin/
CMD ./startup.sh

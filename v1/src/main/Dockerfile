FROM ubuntu
MAINTAINER jyothi
RUN docker start doc_jen
RUN docker attach doc_jen
RUN apt-get update
CMD apt-get install -y apache2
CMD systemctl status apache2
EXPOSE 80


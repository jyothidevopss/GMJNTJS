FROM ubuntu
MAINTAINER jyothi
CMD sudo docker start doc_jen
CMD sudo docker attach doc_jen
RUN apt-get update
CMD apt-get install -y apache2
CMD systemctl status apache2
EXPOSE 80


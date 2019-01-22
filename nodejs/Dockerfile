
FROM ubuntu:18.04
WORKDIR /var/www

# NODEJS
RUN apt-get update && \
    apt-get -y install nano && \
    apt-get -y install sudo wget && \
    sudo apt-get -y install nodejs && \
    sudo apt-get -y install npm

RUN apt-get update && \
    sudo apt-get -y install git

EXPOSE 8888

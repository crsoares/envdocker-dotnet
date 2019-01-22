
FROM ubuntu:18.04
WORKDIR /var/www

# DOT NET
RUN apt-get update && \
    apt-get -y install nano && \
    apt-get -y install git && \
    apt-get -y install net-tools && \
    apt-get -y install sudo wget && \
    wget -q https://packages.microsoft.com/config/ubuntu/18.04/packages-microsoft-prod.deb && \
    sudo dpkg -i --force-depends packages-microsoft-prod.deb && \
    sudo apt-get -y install software-properties-common && \
    sudo add-apt-repository -y universe && \
    sudo apt-get -y install apt-transport-https && \
    sudo apt-get update && \
    sudo apt-get -y install dotnet-sdk-2.2

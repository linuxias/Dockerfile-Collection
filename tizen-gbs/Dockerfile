FROM ubuntu:16.04
LABEL maintainer = "Seungha Son <linuxias@gmail.com>"

RUN echo "deb [trusted=yes] http://download.tizen.org/tools/latest-release/Ubuntu_16.04/ /" >> /etc/apt/sources.list

RUN apt-get update
RUN apt-get install gbs -y
RUN apt-get install mic -y
RUN apt-get upgrade -y

COPY gbs.conf /root/.gbs.conf

FROM ubuntu:16.04
RUN apt update && apt install -y apt-mirror
COPY ./mirror.list /etc/apt/mirror.list
CMD apt-mirror

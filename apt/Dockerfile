FROM ubuntu:16.04
COPY ./mirror.list /etc/apt/mirror.list
RUN apt update && apt install -y apt-mirror
CMD apt-mirror
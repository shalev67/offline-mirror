FROM ubuntu:16.04
COPY ./bandersnatch.conf /etc/bandersnatch.conf
RUN apt update && apt install -y python3-pip python3 python3-dev
RUN pip3 install bandersnatch
CMD bandersnatch mirror
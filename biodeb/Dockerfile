FROM debian:latest

WORKDIR /dev

RUN apt-get -yq update && apt-get -yq install build-essential cmake imagemagick git

RUN git clone https://github.com/jake-dds/nbis_v5.git

WORKDIR /dev/biomount

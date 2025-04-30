FROM ubuntu:24.04

RUN apt-get update \
  && apt-get install -y software-properties-common zip file \
  && add-apt-repository ppa:ubuntugis/ppa \
  && apt-get update \
  && apt-get install -y gdal-bin \
  && rm -rf /var/lib/apt/lists/*

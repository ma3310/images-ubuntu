# Docker Hub: ma3310/ubuntu:20.04-tools
FROM ubuntu:20.04

ENV LANG=C.UTF-8
ENV LC_ALL=C.UTF-8

# net-tools: ifconfig
RUN apt-get update && apt-get upgrade -y && apt install -y \
  curl \
  iproute2 \
  iputils-ping \
  less \
  lynx \
  mariadb-client \
  mycli \
  net-tools \
  nmap \
  openssh-client \
  wget \
  zsh \
  && apt-get clean && rm -rf /var/lib/apt/lists/*
  
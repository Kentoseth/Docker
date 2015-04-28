# 
# Dockerfile to use as a base for python
#
# Combines Ubuntu + Python
#
# https://github.com

FROM ubuntu:14.04
MAINTAINER "Moe" <kentoseth@devcroo.com>

# Prerequisites

RUN \
  sudo apt-get update && \
  sudo apt-get -y upgrade && \
  sudo apt-get install -y python2.7 python2.7-dev python-pip && \
  sudo apt-get clean && \
  sudo rm -rf /var/lib/apt/lists/*
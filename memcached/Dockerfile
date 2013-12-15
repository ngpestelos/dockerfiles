# Memcached
# VERSION	1.0
#

# use dotCloud's base image
FROM ubuntu

MAINTAINER ngpestelos

# make sure package repository is up to date
RUN echo "deb http://archive.ubuntu.com/ubuntu precise main universe" > /etc/apt/sources.list
RUN apt-get update

# install memcached
RUN apt-get install -y memcached

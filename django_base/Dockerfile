FROM ubuntu:14.04.3
MAINTAINER mithun@openkerala.com

RUN apt-get update

RUN apt-get install -qyy \
    -o APT::Install-Recommends=false -o APT::Install-Suggests=false \
    build-essential python-pip python-virtualenv libffi6 openssl libmysqlclient-dev python-dev

RUN ARCHFLAGS=-Wno-error=unused-command-line-argument-hard-error-in-future pip install django==1.8 MySQL-python==1.2.5 south freeze wheel

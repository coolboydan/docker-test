FROM dan/centos:7.1

MAINTAINER Dan,Zheng <zcy@nicecale.com>

ENV TZ "Asia/ShenZhen"
ENV TEAM Dan

RUN yum install -y python-setuptools && \
    easy_install supervisor

EXPOSE 22
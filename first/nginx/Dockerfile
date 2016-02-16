FROM run/centos:7.1

MAINTAINER Dan,Zheng <zcy@nicecale.com>

ENV TZ "Asia/ShenZhen"
ENV TEAM Dan

ADD supervisord.conf /etc/supervisord.conf

RUN yum -y install nginx && \
     yum clean all

EXPOSE	80 443
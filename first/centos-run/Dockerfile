FROM base/centos:7.1

MAINTAINER Dan,Zheng <zcy@nicecale.com>

ENV TZ "Asia/ShenZhen"
ENV TEAM Dan

ADD supervisord.conf /etc/supervisord.conf

RUN mkdir -p /etc/supervisor.conf.d && \
    mkdir -p /var/log/supervisor

ENTRYPOINT ["/usr/bin/supervisord", "-n", "-c", "/etc/supervisord.conf"]
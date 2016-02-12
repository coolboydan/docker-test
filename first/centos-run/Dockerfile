FROM base/centos:7.1

MAINTAINER Dan,Zheng <zcy@nicecale.com>

ENV TZ "Asia/ShenZhen"
ENV TEAM Dan

ENTRYPOINT ["/usr/bin/supervisord", "-n", "-c", "/etc/supervisord.conf"]
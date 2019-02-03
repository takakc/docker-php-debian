FROM mysql/mysql-server:8.0
MAINTAINER kankan


ENV LANG=ja_JP.UTF-8

COPY ./setting/my.cnf /etc/
COPY ./setting/mysql_character_set.conf.d /etc/mysql/conf.d/

RUN rm -f /etc/localtime && \
    ln -fs /usr/share/zoneinfo/Asia/Tokyo /etc/localtime

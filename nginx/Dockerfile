FROM nginx:stable-alpine
MAINTAINER kankan
ARG username="kan"
ARG password="kankan"


COPY setting/server.conf /etc/nginx/conf.d/
RUN chmod 755 /etc/nginx/conf.d/server.conf
RUN mv /etc/nginx/conf.d/default.conf /etc/nginx/conf.d/default.conf_bk

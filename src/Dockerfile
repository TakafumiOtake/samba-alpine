FROM takafumiotake/s6-alpine

MAINTAINER takafumiotake<tikutaka.dev@gmail.com>

COPY etc /etc

RUN apk add --update --no-cache \
        samba \
        samba-common-tools \
    && mkdir -m 777 /share

VOLUME /share

EXPOSE 137/udp 138/udp 139 445

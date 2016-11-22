FROM takafumiotake/s6-alpine

MAINTAINER takafumiotake<tikutaka.dev@gmail.com>

RUN apk add --update --no-cache \
        samba \
        samba-common-tools \
    && mkdir -m 777 /share

VOLUME /shared

EXPOSE 137/udp 138/udp 139 445

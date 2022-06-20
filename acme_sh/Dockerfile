ARG BUILD_FROM
FROM $BUILD_FROM

RUN apk add --no-cache openssl && \
    rm -rf /var/cache/apk/*

RUN curl https://get.acme.sh | sh

ENV LANG C.UTF-8

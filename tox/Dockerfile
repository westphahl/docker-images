FROM alpine:3.8

RUN apk add --no-cache \
        build-base \
        libffi-dev \
        openssh \
        openssl \
        openssl-dev \
        python3 \
        python3-dev \
        rsync \
    && ln -s /usr/bin/python3 /usr/bin/python \
    && pip3 install --no-cache-dir tox

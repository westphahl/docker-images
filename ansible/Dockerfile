FROM python:alpine3.7

RUN apk add --no-cache \
        build-base \
        libffi-dev \
        openssl-dev \
        python3-dev \
    && pip install ansible requests \
    && apk del \
        build-base \
        libffi-dev \
        openssl-dev \
        python3-dev

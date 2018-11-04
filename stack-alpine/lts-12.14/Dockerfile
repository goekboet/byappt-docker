FROM alpine:3.8

RUN apk update && \
    apk add ghc wget musl-dev zlib-dev && \
    wget -qO- https://get.haskellstack.org/ | sh
COPY config.yaml /etc/stack/config.yaml
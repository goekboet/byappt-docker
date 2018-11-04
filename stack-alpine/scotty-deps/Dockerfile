FROM stack-build-alpine:ghc-8.4.3
COPY . /usr/local
RUN cd /usr/local/base-scotty && \
    stack build --only-snapshot && \
    cd / && \
    rm -r /usr/local/base-scotty
FROM alpine:latest

RUN set -ex && \
    apk add --no-cache bash gcc musl-dev neovim cmake gtest-dev git

RUN set -ex && \
    rm -f /usr/libexec/gcc/x86_64-alpine-linux-musl/6.4.0/cc1obj && \
    rm -f /usr/libexec/gcc/x86_64-alpine-linux-musl/6.4.0/lto1 && \
    rm -f /usr/libexec/gcc/x86_64-alpine-linux-musl/6.4.0/lto-wrapper && \
    rm -f /usr/bin/x86_64-alpine-linux-musl-gcj

ENTRYPOINT ["/bin/bash"]

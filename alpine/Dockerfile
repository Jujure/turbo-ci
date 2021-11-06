FROM alpine:3.14.2

LABEL maintainer="Julien CLEMENT <julien.clement@epita.fr> [https://juju.re]"

RUN apk update && apk upgrade

RUN apk add gcc clang \
        make meson cmake autoconf autoconf-archive automake libtool-doc \
        musl \
        g++ \
        llvm11

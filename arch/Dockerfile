FROM archlinux:base-devel

LABEL maintainer="Julien CLEMENT <julien.clement@epita.fr> [https://juju.re]"

RUN pacman -Syy

RUN pacman -Sy --noconfirm gcc clang \
        base-devel meson cmake autoconf autoconf-archive libtool \
        musl \
        python3 python-pip \
        gtest \
        libev \
        boost \
        openssl \
        llvm \
        grub libisoburn arch-install-scripts mtools \
        && pacman -Scc --noconfirm

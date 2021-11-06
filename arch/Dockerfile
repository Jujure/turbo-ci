FROM archlinux:base-devel

RUN pacman -Syy

RUN pacman -Sy --noconfirm gcc clang \
        base-devel meson cmake autoconf autoconf-archive \
        musl \
        python3 python-pip \
        gtest \
        libev \
        boost \
        openssl \
        llvm \
        && pacman -Scc --noconfirm

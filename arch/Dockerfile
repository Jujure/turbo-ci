FROM archlinux:base-devel

RUN pacman -Syy

RUN pacman -Sy --noconfirm gcc clang \
        base-devel meson cmake autoconf autoconf-archive \
        musl \
        llvm

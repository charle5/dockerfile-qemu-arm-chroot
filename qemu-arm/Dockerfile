FROM nfnty/arch-devel:latest
MAINTAINER charle5 <charle5@example.com>

ENV ARCH_FRONTEND noninteractive

RUN pacman -Syu
RUN pacman -U https://aur.archlinux.org/packages/qe/qemu-arm-static/qemu-arm-static.tar.gz

WORKDIR /
VOLUME /data

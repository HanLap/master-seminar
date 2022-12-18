# syntax=docker/dockerfile:1.4

FROM archlinux:latest


RUN pacman -Syu --noconfirm
RUN pacman -S --noconfirm texlive-most python python-pygments


WORKDIR /work

CMD [ "/bin/bash" ]
FROM archlinux:latest
#FROM ekultails/steamos:latest

ENV OUTPUT_DIR /output

RUN \
    pacman --noconfirm -Syy && \
    pacman --noconfirm -S arch-install-scripts \
      base-devel \
      btrfs-progs \
      dosfstools \
      e2fsprogs \
      exfatprogs \
      parted \
      sudo \
      zip

WORKDIR /workdir/scripts

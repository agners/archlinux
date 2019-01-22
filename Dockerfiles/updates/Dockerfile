FROM agners/archlinuxarm-arm32v7:currenttar
LABEL maintainer "ArchLinux ARM Dockerimage Maintainers"

RUN    pacman --noconfirm -Syu \
    && rm -f \
      /var/cache/pacman/pkg/* \
      /var/lib/pacman/sync/* \
      /etc/pacman.d/mirrorlist.pacnew

CMD ["/bin/bash"]

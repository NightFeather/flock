FROM archlinux
RUN pacman -Syu --noconfirm
RUN pacman -S --noconfirm bird vim wireguard-tools

RUN ln -s /usr/share/zoneinfo/Asia/Taipei /etc/localtime

RUN mkdir /run/bird/

CMD [ "/usr/bin/bird", "-f" ]

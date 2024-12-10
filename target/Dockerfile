FROM debian:latest

RUN apt update && apt install -y dialog apt-utils iputils-ping iproute2 curl gpg rsyslog fail2ban openssh-server logwatch && mkdir /var/cache/logwatch

CMD ["bash"]




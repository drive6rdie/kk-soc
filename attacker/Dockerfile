FROM debian:latest

RUN apt update && apt install -y dialog apt-utils iputils-ping iproute2 hydra net-tools nmap && wget https://raw.githubusercontent.com/danielmiessler/SecLists/refs/heads/master/Passwords/richelieu-french-top20000.txt -O /root/wordlist.txt

CMD ["bash"]
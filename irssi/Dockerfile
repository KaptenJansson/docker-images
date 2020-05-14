FROM kaptenjansson/sshd
MAINTAINER KaptenJansson
RUN apt-get install -y tmux irssi
ADD bashrc /root/.bashrc
CMD /usr/sbin/sshd -D

FROM ubuntu:latest
MAINTAINER Chris Jones <cmsj@tenshu.net>

# Install Samba
RUN apt-get update && apt-get install -y openssh-client rsync ; apt-get clean

ENTRYPOINT ["/usr/bin/rsync"]


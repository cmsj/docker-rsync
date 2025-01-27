FROM ubuntu:latest
MAINTAINER Chris Jones <cmsj@tenshu.net>

# Install Samba
RUN apt-get update && apt-get install -y openssh-client rsync ; apt-get clean

# No entrypoint, take care of that yourself with a command that does something rsync related

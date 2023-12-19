# rsync

Docker container for rsync with openssh-client installed.

The base image is ubuntu:latest and this container will be automatically built and published whenever either the Ubuntu base image changes, or when the dependency tree of rsync/openssh-client changes. This is all handled by GitHub Actions automatically.

There is no Entrypoint set for the container, so you will need to specify a command when you run it (presumably an rsync command).

FROM fedora:latest

RUN dnf -y install rpminspect && dnf -y clean all

ENTRYPOINT ["/usr/bin/rpminspect"]

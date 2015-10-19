# Dockerfile for sniproxy on Fedora
FROM fedora:22

MAINTAINER anton.belodedenko@gmail.com

RUN yum -y install udns-devel sniproxy

CMD ["/usr/sbin/sniproxy", "-c", "/data/sniproxy.conf", "-f"]

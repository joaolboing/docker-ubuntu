FROM ubuntu:16.04

MAINTAINER joaolboing <joaolboing@gmail.com>

RUN apt-get update && \
apt-get install -y --no-install-recommends ca-certificates && \
apt-get -y dist-upgrade && \

apt-get autoremove -y && \

apt-get clean all && \
rm -rf /var/lib/apt/lists
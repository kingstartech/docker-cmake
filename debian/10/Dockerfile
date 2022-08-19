ARG DEBIAN_TAG=10
FROM debian:${DEBIAN_TAG}

RUN ln -sf /usr/share/zoneinfo/Asia/Shanghai  /etc/localtime
RUN date -R && apt-get update
RUN apt-get install -y gcc cmake build-essential git libssl-dev

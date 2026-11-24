FROM ubuntu:24.04

RUN apt-get update && apt-get install -y \
    iproute2 \
    iputils-ping \
    net-tools \
    traceroute \
    tcpdump \
    && rm -rf /var/lib/apt/lists/*

CMD ["sleep", "infinity"]

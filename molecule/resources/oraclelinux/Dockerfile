FROM oraclelinux:8-slim

RUN microdnf install -y python3 python3-pip sudo \
    && ln -s /usr/bin/python3 /usr/bin/python \
    && microdnf clean all

RUN mkdir -p /tmp/.ansible && chmod 1777 /tmp /tmp/.ansible
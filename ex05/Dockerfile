FROM ubuntu:18.04

LABEL title="My Ubuntu"

ARG MESSAGE="complete"

RUN adduser --disabled-password --gecos "" jungminchae
RUN whoami

USER jungminchae
RUN whoami

RUN echo $MESSAGE

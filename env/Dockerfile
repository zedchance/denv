# docker environment

FROM ubuntu:20.04
WORKDIR /
ENV DEBIAN_FRONTEND noninteractive

RUN apt-get update && \
    apt-get -y install vim git zsh curl && \
    apt-get clean

ADD setup /
RUN /setup

CMD ["bin/zsh"]


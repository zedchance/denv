# docker environment for C

FROM zedchance/env

RUN apt-get update && \
    apt-get -y install clang clangd libssl-dev && \
    apt-get clean

CMD ["bin/zsh"]


FROM ubuntu
SHELL ["/bin/bash", "-c"]
RUN mkdir /hello && touch greeting
WORKDIR /hello

# /bin/bash と出力
RUN echo $0 > greeting
SHELL ["/bin/sh", "-c"]

# /bin/sh と出力
RUN echo $0 >> greeting
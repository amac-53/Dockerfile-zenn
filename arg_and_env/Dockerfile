ARG VERSION="18.04"
FROM ubuntu:${VERSION}

ARG TMP1="HI"
ENV TMP2="HELLO"

RUN mkdir hello
WORKDIR /hello

# Dockerfile 内では共にアクセス可能だが，ターミナルで echo $TMP1 とすると何も出力されない
RUN echo $TMP1 >> greeting
RUN echo $TMP2 >> greeting
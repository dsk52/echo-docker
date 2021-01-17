FROM golang:1.15.6-alpine

WORKDIR $GOPATH/src

ENV GO111MODULE=on

RUN apk update && \
    apk add --no-cache \
    alpine-sdk \
    git

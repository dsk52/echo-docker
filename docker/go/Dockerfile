FROM golang:1.15.6-alpine

WORKDIR $GOPATH/src

ENV GO111MODULE=off

RUN apk update && \
    apk add --no-cache \
    alpine-sdk \
    git

RUN go get -u github.com/cosmtrek/air

ENV GO111MODULE=on

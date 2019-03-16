FROM golang:alpine AS builder

RUN apk update && apk upgrade && \
  apk add --no-cache git openssh curl

RUN curl https://raw.githubusercontent.com/golang/dep/master/install.sh | sh

WORKDIR /go/src/app
FROM golang:1.9.2-alpine3.7

RUN apk add --update git

RUN go get -u github.com/labstack/echo/...

# go get github.com/stretchr/testify

WORKDIR /volumes/echo

ENTRYPOINT go run src/server.go

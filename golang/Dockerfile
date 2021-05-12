FROM golang:1.12.5-alpine3.9

RUN apk update && apk upgrade && \
    apk add --no-cache git

RUN go get github.com/sirupsen/logrus
RUN go get github.com/buaazp/fasthttprouter
RUN go get github.com/valyala/fasthttp
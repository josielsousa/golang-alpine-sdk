FROM golang:1.14.5-alpine

RUN apk add --no-cache --update ca-certificates openssl alpine-sdk

RUN go get -u golang.org/x/tools/... && \
    go get -u golang.org/x/lint/golint && \
    go get -u github.com/haya14busa/goverage && \
    go get -u github.com/kyoh86/richgo && \
    go get -u github.com/gorilla/mux && \
    go get -u github.com/sirupsen/logrus && \
    go get github.com/joho/godotenv/cmd/godotenv

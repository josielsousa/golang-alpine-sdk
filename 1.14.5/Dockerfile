FROM golang:1.14.5-alpine

RUN apk add --no-cache --update ca-certificates openssl alpine-sdk

RUN go get -u golang.org/x/tools/... 
RUN go get -u golang.org/x/lint/golint 
RUN go get -u github.com/haya14busa/goverage 
RUN go get -u github.com/kyoh86/richgo 
RUN go get github.com/joho/godotenv/cmd/godotenv

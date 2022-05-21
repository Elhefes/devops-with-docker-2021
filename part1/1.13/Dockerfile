FROM golang:1.16-alpine

COPY . /example-backend
WORKDIR /example-backend

RUN go build
EXPOSE 8080
CMD ./server
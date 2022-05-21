FROM golang:1.16-alpine

ENV REQUEST_ORIGIN=http://localhost:5000

COPY . /example-backend
WORKDIR /example-backend

RUN go build
EXPOSE 8080
CMD ./server
FROM golang:1.18-alpine

WORKDIR /app
COPY . .

RUN go build -o api

expose 8080

CMD ["./api"]
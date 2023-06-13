FROM golang:1.20-alpine

WORKDIR /app

COPY . ./

RUN go mod download

RUN go build -o /internship

EXPOSE 9090

CMD [ "/internship" ]
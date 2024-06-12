FROM golang:1.22-alpine AS builder

WORKDIR /src

COPY /main .

RUN go mod init aidansparapani/fullcycle-exercises/docker/go && \
    go build main.go 

FROM scratch

WORKDIR /

COPY --from=builder /src / 

CMD ["./main"]

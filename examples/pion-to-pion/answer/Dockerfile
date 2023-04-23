FROM golang:1.20

ENV GO111MODULE=on
RUN go install github.com/guoguov/webrtc/examples/pion-to-pion/answer@latest

CMD ["answer"]

EXPOSE 50000

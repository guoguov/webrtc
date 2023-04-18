FROM golang:1.20

ENV GO111MODULE=on
RUN go install gitlab.mty.wang/sgguo/webrtc/examples/pion-to-pion/answer@latest

CMD ["answer"]

EXPOSE 50000

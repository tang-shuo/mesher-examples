FROM golang:1.11
ADD . /go/src/github.com/go-chassis/mesher-examples/protocol/grpc-go/helloworld/greeter_client
WORKDIR /go/src/github.com/go-chassis/mesher-examples/protocol/grpc-go/helloworld/greeter_client

RUN go install github.com/go-chassis/mesher-examples/protocol/grpc-go/helloworld/greeter_client
ENTRYPOINT /go/bin/greeter_client

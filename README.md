# proto gen [grpc-gateway](https://github.com/grpc-ecosystem/grpc-gateway) for [go-micro](https://github.com/micro/go-micro)

This is original a fork from [protoc-gen-grpc-gateway](https://github.com/grpc-ecosystem/grpc-gateway/tree/master/protoc-gen-grpc-gateway)

```bash
protoc -I/usr/local/include -I. \
  -I$GOPATH/src \
  --micro-gateway_out=logtostderr=true:. \
  path/to/your_service.proto
```
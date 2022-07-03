# api
gRPC interface definition.

- [How do Protocol Buffers Work?](https://developers.google.com/protocol-buffers/docs/overview#work)

# Generate gRPC services

## Install service generators
- [Install protoc.](https://grpc.io/docs/protoc-installation/)
- Add protoc binaries to system path.

### Go lang
- Run `go install google.golang.org/protobuf/cmd/protoc-gen-go@latest`.
- Run `go install google.golang.org/grpc/cmd/protoc-gen-go-grpc@latest`.
- Run `go install github.com/bufbuild/buf/cmd/buf@latest`.
- Run `buf generate`.


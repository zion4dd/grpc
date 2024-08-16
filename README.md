### grpc basics tutorial

`https://grpc.io/docs/languages/python/basics/`

### protobuf guide

`https://protobuf.dev/programming-guides/proto3/`

### helloworld.proto

python -m grpc_tools.protoc -I../../protos --python_out=. --pyi_out=. --grpc_python_out=. ../../protos/helloworld.proto

### pip install

pip install grpcio grpcio-tools grpcio-reflection

### my

python -m grpc_tools.protoc -I. --python_out=. --pyi_out=. --grpc_python_out=. my.proto
python -m grpc_tools.protoc -I./protos --python_out=. --pyi_out=. --grpc_python_out=. protos/my.proto

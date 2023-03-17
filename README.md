# gRPC-Quick-Start

https://grpc.io/docs/languages/python/quickstart/

Compile the proto files to generate 
1. helloworld_pb2_grpc.py
2. helloword_pb2.py
3. helloworld_pb2.pyi
`python -m grpc_tools.protoc -I protos --python_out=. --pyi_out=. --grpc_python_out=. protos/helloworld.proto`

```
python greeter_server.py
python greeter_client.py
```

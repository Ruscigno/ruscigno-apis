.PHONY: build
build:
	~/projects/protoc-3.20.1-linux-x86_64/bin/protoc -I=./v1 --go_out=../../ruscigno-gosdk/ ./v1/*.proto --go-grpc_out=../../ruscigno-gosdk/

.PHONY: build-python
build-python:
	protoc -I=./v1 --python_out=../../ticker-beats-exchange-integration/ruscigno-apis ./v1/*.proto
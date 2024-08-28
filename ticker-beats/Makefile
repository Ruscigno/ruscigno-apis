.PHONY: build
build:
	protoc -I=./v1 --go_out=../../ruscigno-gosdk/ ./v1/*.proto --go-grpc_out=../../ruscigno-gosdk/

.PHONY: build-python
build-python:
	protoc -I=./v1 --python_out=../../ticker-beats-exchange-integration/ruscigno-apis ./v1/*.proto

.PHONY: build-v2
build-v2:
	protoc -I=./v2 --go_out=/home/sander/projects/TradingControl/ ./v2/*.proto

.PHONY: build-v3
build-v3:
	protoc -I=./v3 --go_out=../../ruscigno-gosdk/ ./v3/*.proto --go-grpc_out=../../ruscigno-gosdk/
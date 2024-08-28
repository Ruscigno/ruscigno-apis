#!/bin/bash
export DST_DIR="../../ruscigno-gosdk/grpc-health-check/v1" #change it as needed
export SRC_DIR="./v1/proto"
protoc -I=$SRC_DIR --go_out=$DST_DIR $SRC_DIR/*.proto --go-grpc_out=$DST_DIR
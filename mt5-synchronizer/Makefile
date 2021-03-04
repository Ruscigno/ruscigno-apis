#!/bin/bash
export DST_DIR="../../ruscigno-gosdk/mt5-synchronizer/v1"
export SRC_DIR="./v1"
protoc -I=$SRC_DIR --go_out=$DST_DIR $SRC_DIR/*.proto --go-grpc_out=$DST_DIR
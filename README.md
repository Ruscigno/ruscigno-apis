# Ruscigno APIs
Single source of truth for all my public APIs.

## How to generate it
1. Clone github.com/ruscigno/ruscigno-gosdk repo

2. export both variables

`export DST_DIR="../ruscigno-gosdk/mt5-synchronizer/v1"`
`export SRC_DIR="./mt5-synchronizer/v1"`

3. generate the protos

`protoc -I=$SRC_DIR --go_out=$DST_DIR $SRC_DIR/*.proto --go-grpc_out=$DST_DIR`
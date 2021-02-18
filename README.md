# Ruscigno APIs
Single source of truth for all my public APIs.

## How to generate it
1. define both variables
`export DST_DIR="./generated-protos/mt5-background/v1"`
`export SRC_DIR="./mt5-background/v1"`

2. generate protos
`protoc -I=$SRC_DIR --go_out=$DST_DIR $SRC_DIR/deal.proto`
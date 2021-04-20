## v0.20.5
- fix: enum values

## v0.20.4
- fix: expiration_time as int32

## v0.20.3
- fix: TickerBeatsResponse

## v0.20.2
- feat: improve names

## v0.20.1
- feat: snake names

## v0.20.0
- feat: ticker beats synch, try II

## v0.19.11
- feat: add server time to the request

## v0.19.10
- feat: add Direction field to Orders model

## v0.19.9
- feat: add TradeRequest on signal beats response

## v0.19.8
- feat: rollback SignalType

## v0.19.7
- feat: improving field name

## v0.19.6
- feat: created, updated, deleted as int64

## v0.19.5
- feat: add beats type enum

## v0.19.4
- feat: add beats type to the request

## v0.19.3
- feat: return orders and positions 

## v0.19.2
- feat: datetime as integer

## v0.19.1
- feat: add ID to the model

## v0.19.0
- feat: change on SignalResult

## v0.18.0
- feat: update transactions model

## v0.17.11
- feat: add magic number to positions

## v0.17.10
- feat: return a list of positions instead of deals

## v0.17.9
- fix: struct response name

## v0.17.8
- feat: only one ticker service

## v0.17.6
- fix: services signatures

## v0.17.5
- fix: names

## v0.17.4
- feat: implementation of TickerTrades

## v0.17.3
- feat: improve TickerBeats response

## v0.17.2
- fix: CreateTradeTransaction

## v0.17.1
- fix: TransactionsService name

## v0.17.0
- feat: signal service

## v0.16.1
- feat: add server time field
## v0.16.0
- feat: update name to ticker

## v0.15.2
- feat: account_id in the request
  
## v0.15.1
- feat: server time of the position v2

## v0.15.0
- feat: server time of the position
  
## v0.14.2
- feat: additional fields

## v0.14.1
- fix: field name
  
## v0.14.0
- feat: rolling back to int64
- feat: creation_order

## v0.13.8
- feat: naming improvements

## v0.13.7
- feat: fix name on repeated fields
  
## v0.13.6
- fix: TradeRequestActions

## v0.13.6
- fix: expiration should be int64
  
## v0.13.5
- feat: adding model ID 
  
## v0.13.4
- fix: cannot use type, changing to trade_type 2
  
## v0.13.3
- fix: cannot use type, changing to trade_type
- feat: changing to int64 as it could be as big as it
  
## v0.13.2
- fix: typo on TradeTransactionType
  
## v0.13.1
- feat: repeated requests 
  
## v0.13.0
- feat: trade transation
  
## 0.12.0
- create entities in bulk

## 0.11.0
- licese

## 0.10.0
- fix: magic could be a int64 number

## 0.8.0
- timestamp are actually a int64

## 0.7.0
- could not use protobuf.Timestamp

## 0.6.0
- removing order number from order

## 0.4.0
- remove login field as it is the same as account_id

## 0.3.0
- Wrong sequence

## 0.2.0
- Change name from modified to updated

## 0.1.0
- Create the mql5 backend service with endpoints to create entities (`Order`, `Deal`, `Position` and `Account`)
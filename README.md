# Trading System

A simple trading system simulating price movements from order placements.

## Market data engine
This module should mock market data for symbols ‘AAPL’, ‘TSLA’ and ‘GOOG’. Each symbol’s market data should be within a prespecified band. This band should be configurable. Market data should have 3 values. Best Bid, Best Offer and Last trade price.

## Order placement engine
Users must be able to place orders via this module. User should be able to provide the symbol name, order type (limit or market), order qty and the price if limit order. All orders should be written to a db including the timestamp.

## Matching engine
This module is responsible for matching orders of users. Orders should be matched on a price – time priority basis. You can find enough articles in internet on how this simple matching algorithm works if you need any further information. All trades should be written to a db including the timestamp.

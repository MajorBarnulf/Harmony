# Exchange

## Summary

An exchange is a succession of <mark>messages</mark> sent over a [connection](./001-connection.md) between a [client](./003-client.md) and a [server](./004-server.md) in a precise context and in a specific order to achieve one operation. Generally a request sent by either of the client or the server and a response sent by the other.

## Description

Exchange are operations initialized by one side of a connection by sending a request that may require a response from the other side.

Exchanges splits into two categories: the ones being initialized by a request from the server and the one bein initialized by the client.

An exchange sent by the server is a variant from a finished enumeration of different possible requests. The same property applies for exchanges initialized by clients.

Some exchanges may require either part of the connection to be in a specific state.

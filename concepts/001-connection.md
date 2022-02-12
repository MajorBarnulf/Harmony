# Connection

## Summary

A connection is a stateless asymetric one-to-one two sided connection passing through internet between a [client](./003-client.md) and a [server](./004-server.md) that can be used to perform [exchanges](./002-exchange.md) where either of the entities taking part in it is passing requests to the other.

## Description

### Intended usage

Connection is the component through which requests will be exchanged successively so the client and server can orgainze and keep track of changes in the state of the server.

It is stateless and must only exists if both side of the connection are ready to communicate and receive <mark>messages</mark>.

*The comportment servers and clients have to follow while the connection is being initialized is not specified.*

The connection is asymetric, the connection can only occur between only one server and only one client so each side can assume the type of messages they could receive.

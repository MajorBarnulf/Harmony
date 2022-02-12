# Client

## Summary

The client is a stateful entity that is able to use a [connection](./001-connection.md).

It has a range of available requests to send to initiate [exchanges](./002-exchange.md) over it's connection and will be sent requests from the server holding the other side of the [connection](./001-connection.md).

## Description

Clients may spontaneously send requests through their connection to a client in order to access or alter the state of the later depending on the request.

Requests that client can send to the server in order to initialize an exchange are variants from a finite enumeration of client requests.

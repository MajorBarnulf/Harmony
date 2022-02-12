# Message

## Summary

Messages are possibly parametrized variants of data passed through [connections](./001-connection.md) by either the client or the server during exchanges.

## Description

A message is a value typed from a finite enumeration that can be sent through a connection.

Some variants of messages hold data fields.

Types of messages can be split in such a way: the one that may be sent by the server and the one that may be sent by the client.

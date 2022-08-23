# Data exchange

To initiate a connection, both sides must establish a bidirectionnal TCP stream, proceed to the handshake in order to establish an encrypted connection and authenticate the user, after what they will be able to exchange signals over the connection.

## TCP connection

The server must be listening for TCP connections on a public endpoint on any ports (default: `42000`).
The client then 

## Handshake

### TODO

## Signal

Signals may be sent spontaneously from both ends.
They are encoded as single-line JSON strings separated by newline characters ([LF](https://en.wikipedia.org/wiki/Newline#Representation)) sent over the encrypted connection.
> The server may assume that each received lines is a separate signal.


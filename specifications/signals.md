# Signals

Signals are serialized events spontaneously sent between clients and server once the connection is established.

A signal should be handled by the receiver according to contracts associated to said signal.

## Encoding

There are essentially two categories of signals, those sent by the client and those sent by the server.

## Mandatory fields

- `id` : number, identificator of the request
- `type` : either `"request"`, `"response"` or `"error"`
- `name` : the name of the specific variant of request / response
- `data` : object holding data associated to the variant

### Example


```json
{
    "id": 8937563975,
    "type": "request",
    "name": "command",
    "data": {
        "name": "profile",
        "message_id":  8976593876593
    },
}
```

## Requests

These are the signals sent by the client to request an action be taken by the server, may involve a server response.

- [`get_users`](./signals/requests/get_users.md)
- [`get_channels`](./signals/requests/get_channels.md)
- [`get_messages`](./signals/requests/get_messages.md)
- [`create_message`](./signals/requests/create_message.md)

## Responses

- [`channels`](./signals/response/channels.md)
- [`users`](./signals/response/users.md)
- [`messages`](./signals/response/messages.md)
- [`message_create`](./signals/response/message_create.md)

## Errors

- [`channel_not_accessible`](./signals/errors/channel_not_accessible.md)

These are the signals sent by the server as a response to a request or as spontaneous notifications of an occuring event.


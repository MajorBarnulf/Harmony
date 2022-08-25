# `get_messages`

Sent by the client to request at most the 100 last messages in a specific channel.

## data

- `channel_id`: identifier of the channel to get messages from.

## response

- [messages](../response/messages.md)

## example

```json
{
    "id": 8937563975,
    "type": "request",
    "name": "get_messages",
    "data": {
        "channel_id": 8796598736
    }
}
```

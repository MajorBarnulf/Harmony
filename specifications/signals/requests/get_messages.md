# `get_messages`

Sent by the client to request at most the 100 last [messages](../../models/message.md) in a specific channel.

## Data

- `channel_id`: identifier of the channel to get [messages](../../models/message.md) from.

## Response

- [messages](../response/messages.md)

## Example

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

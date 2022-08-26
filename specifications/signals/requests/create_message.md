# `create_message`

Sent by the client to request the creation of a [message](../../models/message.md) in a specific [channel](../../models/channel.md) to the server.

## Data

- `channel_id` identifier, for the channel in which to send the message in.
- `content` string, content of the message.

## Response

- [create_message_success](../response/create_message_success.md)
- [channel_not_accessible](../errors/channel_not_accessible.md)

## Example

```json
{
    "id": 8937563975,
    "type": "request",
    "name": "create_message",
    "data": {
        "channel_id": 897659876,
        "content": "lorem ipsum dolor amit",
    }
}
```

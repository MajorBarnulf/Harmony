# `edit_message`

Sent by the client to request changes of the content of a [message](../../models/message.md) in a specific channel to the server.

## Data

- `channel_id` identifier, for the channel in which to send the message in.
- `content` string, content of the message.

## Response

- [edit_message](../response/edit_message_success.md)
- [channel_not_accessible](../errors/channel_not_accessible.md)

## Example

```json
{
    "id": 8937563975,
    "type": "request",
    "name": "edit_message",
    "data": {
        "channel_id": 897659876,
        "content": "lorem ipsum dolor amit",
    }
}
```

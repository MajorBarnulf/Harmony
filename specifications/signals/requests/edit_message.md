# `edit_message`

Sent by the client to request changes of the content of a message in a specific channel to the server.

## data

- `channel_id` identifier, for the channel in which to send the message in
- `content` string, content of the message

## response

- [edit_message](../response/edit_message_success.md)
- [channel_not_accessible](../errors/channel_not_accessible.md)

## example

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

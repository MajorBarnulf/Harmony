# `edit_message`

Sent by the client to request changes of the content of a message in a specific channel to the server.

## data

- `message` the created message

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
        "message": {
        	"message_id": 87698576987,
        	"author_id": 37568793569,
        	"content": "lorem ipsum",
        	"creation_date": 78496987687,
        }
    }
}
```

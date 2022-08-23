# Message

The message model is a [model](../models.md) representinh the data of a message sent in a [channel](./channel.md).

## Properties
| key           | type       | example                      |
| ------------- | ---------- | ---------------------------- |
| message_id    | identifier | `87698576987`                |
| channel_id    | identifier | `85629873698`                |
| author_id     | identifier | `37568793569`                |
| content       | string     | `"lorem ipsum"`              |
| creation_date | timestamp  | `78496987687`                |

## Example
```json
{
	"message_id": 87698576987,
	"author_id": 37568793569,
	"content": "lorem ipsum",
	"creation_date": 78496987687,
}
```

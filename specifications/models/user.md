# User

The user model is a [model](../models.md) representing the public data about a user of the server.

## Properties
| key           | type       | example                      |
| ------------- | ---------- | ---------------------------- |
| user_id       | identifier | `37568793569`                |
| name          | string     | `"bob"`                      |
| description   | string     | `"lorem ipsum"`              |
| icon_url      | string     | `"http://place.com/pic.png"` |
| fame          | number     | `353`                        |
| online        | boolean    | `true`                       |
| creation_date | timestamp  | `37568793569`                |

## Example
```json
{
	"user_id": 1234,
	"name": "bob",
	"description": "lorem ipsum",
	"icon_url": "http://place.com/pic.png",
	"fame": 353,
	"online": true,
	"creation_date": 37568793569
}
```

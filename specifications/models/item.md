# Item

The item model is a [model](../models.md) about a cosmetic item that [users](./user.md) may create, own or give.

## Properties
| key           | type       | example                      |
| ------------- | ---------- | ---------------------------- |
| item_id       | identifier | `56892938776`                |
| owner_id      | identifier | `37568793569`                |
| name          | string     | `"shiny thing"`              |
| description   | string     | `"a shiny item"`             |
| color         | number     | `16766720`                   |
| icon_url      | string     | `"http://place.com/pic.png"` |
| author_id     | identifier | `37568793569`                |
| creation_date | timestamp  | `78496987687`                |

## Example
```json
{
"item_id": 56892938776,
"owner_id": 37568793569,
"name": "shiny thing",
"description": "a shiny item",
"color": "16766720",
"icon_url": "http://place.com/pic.png",
"author_id": 37568793569,
"creation_date": 78496987687,
}
```

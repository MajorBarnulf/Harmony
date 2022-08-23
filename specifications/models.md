# Models

Models are the data that is persistently stored by a server and that clients may request or update through signals.

## Encoding

When sent over a connection, they are serialized as a JSON string with at least the properties described here.

## Primitives

Model fields are of the following types

### number
JSON number, integers inside the inclusive range `[0..2_147_483_647i32]`.
> They may be encoded as 32 bit signed integers.

### string
JSON string, entirely composed of valid UTF-8 encoded characters.

### identifier
JSON number, positive integers inside the inclusive range `[0..18_446_744_073_709_551_615]`.
> They may be encoded as 64 bit unsigned integers.

Represents a unique identifier for an entity within a collection.

### timestamp
JSON number, positive integers inside the inclusive range `[0..18_446_744_073_709_551_615]`.
> They may be encoded as 64 bit unsigned integers.

## Structures
- [channel](./models/channel.md)
- [message](./models/message.md)
- [role](./models/role.md)
- [user](./models/user.md)

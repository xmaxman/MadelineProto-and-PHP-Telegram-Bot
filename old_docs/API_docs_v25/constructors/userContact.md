---
title: userContact
description: userContact attributes, type and example
---
## Constructor: userContact  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|:-------------:|---------:|
|id|[int](../types/int.md) | Required|
|first\_name|[string](../types/string.md) | Required|
|last\_name|[string](../types/string.md) | Required|
|username|[string](../types/string.md) | Required|
|access\_hash|[long](../types/long.md) | Required|
|phone|[string](../types/string.md) | Required|
|photo|[UserProfilePhoto](../types/UserProfilePhoto.md) | Required|
|status|[UserStatus](../types/UserStatus.md) | Required|



### Type: [User](../types/User.md)


### Example:

```
$userContact = ['_' => 'userContact', 'id' => int, 'first_name' => string, 'last_name' => string, 'username' => string, 'access_hash' => long, 'phone' => string, 'photo' => UserProfilePhoto, 'status' => UserStatus, ];
```  

The following syntaxes can also be used:

```
$userContact = '@username'; // Username

$userContact = 44700; // bot API id (users)
$userContact = -492772765; // bot API id (chats)
$userContact = -10038575794; // bot API id (channels)

$userContact = 'user#44700'; // tg-cli style id (users)
$userContact = 'chat#492772765'; // tg-cli style id (chats)
$userContact = 'channel#38575794'; // tg-cli style id (channels)
```
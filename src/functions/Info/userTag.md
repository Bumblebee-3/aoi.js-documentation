---
title: $userTag 
description: $userTag will return a user's username and discriminator.
id: userTag
---

`$userTag` will return a user's username and discriminator.

## Usage

```php
$userTag[userID?]
```

## Parameters 


| Field     | Type    | Description                                        | Required |
|-----------|---------|----------------------------------------------------| :------: |
| userID?    | integer  | user ID                             | no      |


## Example

This will return your username and discriminator:

```javascript
bot.command({
  name: 'userTag',
  code: `
  $userTag[$authorID]
  `
});
```

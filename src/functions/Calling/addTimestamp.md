---
title: $addTimestamp 
description: $addTimestamp will add a timestamp to an embed.
id: addTimestamp
---

`$addTimestamp` will add a timestamp to an embed.

## Usage

```php
$addTimestamp[ms?]
```

## Parameters 


| Field     | Type    | Description                                        | Required |
|-----------|---------|----------------------------------------------------| :------: |
| ms    | integer  | epoch time                                         | no      |


## Example

This will create a embed with timestamp and description:

```javascript
bot.command({
  name: 'addTimestamp',
  code: `
  $description[Hello!]
  $addTimestamp
  `
});
```

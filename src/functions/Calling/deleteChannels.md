---
title: $deleteChannels 
description: $deleteChannels will delete a multiple channels.
id: deleteChannels
---

`$deleteChannels` will delete a multiple channels.

## Usage

```php
$deleteChannels[...channels]
```

## Parameters 


| Field     | Type    | Description                                        | Required |
|-----------|---------|----------------------------------------------------| :------: |
| channels    | integer  | channel IDs                             | yes      |


## Example

This will delete multiple channels, make sure to replace the arguments:

```javascript
bot.command({
  name: 'deleteChannels',
  code: `
  $deleteChannels[channelID1;channelID2;channelID3;channelID4]
  `
});
```

---
title: $cacheMembers 
description: $cacheMembers will cache all members of a guild.
id: cacheMembers
---

`$cacheMembers` will cache all members of a guild.

## Usage

```php
$cacheMembers[guildID?;returnCount?]
```

## Parameters 


| Field     | Type    | Description                                        | Required |
|-----------|---------|----------------------------------------------------| :------: |
| guildID?    | integer  | guild ID                             | yes      |
| returnCount?    | integer  | return the cached member count <br /> 1. **yes** <br /> 2. **no** (default)  | yes      |


## Example

This will cache all members of the current guild and return the amount of the cached members:

```javascript
bot.command({
  name: 'cacheMembers',
  code: `
  $cacheMembers[$guildID;yes]
  `
});
```

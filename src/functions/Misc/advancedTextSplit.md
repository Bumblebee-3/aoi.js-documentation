---
title: $advancedTextSplit 
description: $advancedTextSplit will split multiple given arguments.
id: advancedTextSplit
---

`$advancedTextSplit` will split multiple given arguments.

## Usage

```php
$advancedTextSplit[text;sep;index;sep?;index?..]
```

## Parameters 


| Field     | Type    | Description                                        | Required |
|-----------|---------|----------------------------------------------------| :------: |
| text    | string  | text to split                             | yes      |
| sep    | string  | seperator                             | yes      |
| index    | integer  | the position of the text you want to seperate | yes      |


## Example

This will split `Hello.`, `Bye.` and `Ok.` and return `Bye.`:

```javascript
bot.command({
  name: 'advancedTextSplit',
  code: `
  $advancedTextSplit[Hello./Bye.|Ok.;/;2;|;1]
  `
});
```

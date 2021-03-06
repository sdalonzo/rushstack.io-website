---
layout: page
navigation_source: api_nav
improve_this_button: false
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@microsoft/node-core-library](./node-core-library.md) &gt; [Text](./node-core-library.text.md) &gt; [padStart](./node-core-library.text.padstart.md)

## Text.padStart() method

Append characters to the start of a string to ensure the result has a minimum length.

<b>Signature:</b>

```typescript
static padStart(s: string, minimumLength: number, paddingCharacter?: string): string;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  s | <code>string</code> |  |
|  minimumLength | <code>number</code> |  |
|  paddingCharacter | <code>string</code> |  |

<b>Returns:</b>

`string`

## Remarks

If the string length already exceeds the minimum length, then the string is unchanged. The string is not truncated.


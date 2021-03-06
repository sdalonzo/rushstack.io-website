---
layout: page
navigation_source: api_nav
improve_this_button: false
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@microsoft/node-core-library](./node-core-library.md) &gt; [PackageName](./node-core-library.packagename.md) &gt; [getScope](./node-core-library.packagename.getscope.md)

## PackageName.getScope() method

The parsed NPM scope, or an empty string if there was no scope. The scope value will always include the at-sign.

<b>Signature:</b>

```typescript
static getScope(packageName: string): string;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  packageName | <code>string</code> |  |

<b>Returns:</b>

`string`

## Remarks

For example, if the parsed input was "<!-- -->@<!-- -->scope/example", then scope would be "<!-- -->@<!-- -->scope".


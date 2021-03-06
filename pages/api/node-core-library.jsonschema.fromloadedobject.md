---
layout: page
navigation_source: api_nav
improve_this_button: false
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@microsoft/node-core-library](./node-core-library.md) &gt; [JsonSchema](./node-core-library.jsonschema.md) &gt; [fromLoadedObject](./node-core-library.jsonschema.fromloadedobject.md)

## JsonSchema.fromLoadedObject() method

Registers a JsonSchema that will be loaded from a file on disk.

<b>Signature:</b>

```typescript
static fromLoadedObject(schemaObject: Object): JsonSchema;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  schemaObject | <code>Object</code> |  |

<b>Returns:</b>

`JsonSchema`

## Remarks

NOTE: An error occurs if the file does not exist; however, the file itself is not loaded or validated until it the schema is actually used.


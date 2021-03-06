---
layout: page
navigation_source: api_nav
improve_this_button: false
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@microsoft/api-extractor-model](./api-extractor-model.md) &gt; [ApiVariable](./api-extractor-model.apivariable.md)

## ApiVariable class

Represents a TypeScript variable declaration.

<b>Signature:</b>

```typescript
export declare class ApiVariable extends ApiVariable_base 
```

## Remarks

This is part of the [ApiModel](./api-extractor-model.apimodel.md) hierarchy of classes, which are serializable representations of API declarations.

`ApiVariable` represents an exported `const` or `let` object such as these examples:

```ts
// A variable declaration
export let verboseLogging: boolean;

// A constant variable declaration with an initializer
export const canvas: IWidget = createCanvas();

```

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(options)](./api-extractor-model.apivariable._constructor_.md) |  | Constructs a new instance of the <code>ApiVariable</code> class |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [containerKey](./api-extractor-model.apivariable.containerkey.md) |  | <code>string</code> |  |
|  [kind](./api-extractor-model.apivariable.kind.md) |  | <code>ApiItemKind</code> |  |
|  [variableTypeExcerpt](./api-extractor-model.apivariable.variabletypeexcerpt.md) |  | <code>Excerpt</code> | An [Excerpt](./api-extractor-model.excerpt.md) that describes the type of the variable. |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [buildCanonicalReference()](./api-extractor-model.apivariable.buildcanonicalreference.md) |  | <b><i>(BETA)</i></b> |
|  [getContainerKey(name)](./api-extractor-model.apivariable.getcontainerkey.md) | <code>static</code> |  |
|  [onDeserializeInto(options, context, jsonObject)](./api-extractor-model.apivariable.ondeserializeinto.md) | <code>static</code> |  |
|  [serializeInto(jsonObject)](./api-extractor-model.apivariable.serializeinto.md) |  |  |


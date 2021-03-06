---
layout: page
navigation_source: api_nav
improve_this_button: false
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@microsoft/rush-lib](./rush-lib.md) &gt; [PnpmOptionsConfiguration](./rush-lib.pnpmoptionsconfiguration.md)

## PnpmOptionsConfiguration class

Options that are only used when the PNPM package manager is selected.

<b>Signature:</b>

```typescript
export declare class PnpmOptionsConfiguration 
```

## Remarks

It is valid to define these options in rush.json even if the PNPM package manager is not being used.

The constructor for this class is marked as internal. Third-party code should not call the constructor directly or create subclasses that extend the `PnpmOptionsConfiguration` class.

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [resolutionStrategy](./rush-lib.pnpmoptionsconfiguration.resolutionstrategy.md) |  | <code>ResolutionStrategy</code> | The resolution strategy that will be used by PNPM. |
|  [strictPeerDependencies](./rush-lib.pnpmoptionsconfiguration.strictpeerdependencies.md) |  | <code>boolean</code> | If true, then Rush will add the "--strict-peer-dependencies" option when invoking PNPM. |


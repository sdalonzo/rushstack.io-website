---
layout: page
navigation_source: api_nav
improve_this_button: false
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@microsoft/ts-command-line](./ts-command-line.md) &gt; [IBaseCommandLineDefinition](./ts-command-line.ibasecommandlinedefinition.md) &gt; [environmentVariable](./ts-command-line.ibasecommandlinedefinition.environmentvariable.md)

## IBaseCommandLineDefinition.environmentVariable property

The name of an environment variable that the parameter value will be read from, if it was omitted from the command-line. An error will be reported if the environment value cannot be parsed.

<b>Signature:</b>

```typescript
environmentVariable?: string;
```

## Remarks

The environment variable name must consist only of upper-case letters, numbers, and underscores. It may not start with a number.

This feature cannot be used when [IBaseCommandLineDefinition.required](./ts-command-line.ibasecommandlinedefinition.required.md) is true, because in that case the environmentVariable would never be used.


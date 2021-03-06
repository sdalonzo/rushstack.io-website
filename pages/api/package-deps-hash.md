---
layout: page
navigation_source: api_nav
improve_this_button: false
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@microsoft/package-deps-hash](./package-deps-hash.md)

## package-deps-hash package

This package builds a JSON object containing the git hashes of all files used to produce a given NPM package. The [Rush](https://rushjs.io/) tool uses this library to implement incremental build detection.

## Remarks

For more info, please see the package [README](https://www.npmjs.com/package/@microsoft/package-deps-hash)<!-- -->.

## Functions

|  Function | Description |
|  --- | --- |
|  [getPackageDeps(packagePath, excludedPaths)](./package-deps-hash.getpackagedeps.md) | Builds an object containing hashes for the files under the specified <code>packagePath</code> folder. |

## Interfaces

|  Interface | Description |
|  --- | --- |
|  [IPackageDeps](./package-deps-hash.ipackagedeps.md) | The data structure returned by [getPackageDeps()](./package-deps-hash.getpackagedeps.md)<!-- -->. |


# BuildApp.AddFlag method

Adds support for a no-value command-line flag.

```csharp
public BuildFlag AddFlag(string template, string description)
```

| parameter | description |
| --- | --- |
| template | The flag template, e.g. `"-q|--quiet"`. |
| description | The flag help description, e.g. `"Suppresses console output"`. |

## Return Value

The added [`BuildFlag`](../BuildFlag.md), which can be used from within a running target to determine whether the flag was set.

## See Also

* class [BuildFlag](../BuildFlag.md)
* class [BuildApp](../BuildApp.md)
* namespace [Faithlife.Build](../../Faithlife.Build.md)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Build.dll -->

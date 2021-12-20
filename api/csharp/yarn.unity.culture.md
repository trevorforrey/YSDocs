# Culture

Struct in [Yarn.Unity](/api/csharp/yarn.unity.md)

Inherits from `System.ValueType`

## Summary


Holds information about a language.


```csharp
[Serializable]
    public struct Culture
    {
    }
```

## Fields

|Name|Description|
|:---|:---|
|[Name](/api/csharp/yarn.unity.culture.name.md)|The unique language ID used to identify a language as RFC 4646. Will be "de-CH" for "German (Switzerland)". Use this for storing settings or identifying a language.|
|[DisplayName](/api/csharp/yarn.unity.culture.displayname.md)|The display name of a language. Will be "German (Switzerland)" for "de-CH". Use this value to present the language in an English UI.|
|[NativeName](/api/csharp/yarn.unity.culture.nativename.md)|The languages name as called in the language itself. Will be "Deutsch (Schweiz) for "de-CH". Use this to present the language in-game so people can find their native language.|

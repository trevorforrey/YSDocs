# YarnProject

Class in [Yarn.Unity](/api/csharp/yarn.unity.md)

Inherits from `ScriptableObject`

## Summary



```csharp
public class YarnProject : ScriptableObject
```

## Fields

|Name|Description|
|:---|:---|
|[baseLocalization](/api/csharp/yarn.unity.yarnproject.baselocalization.md)||
|[compiledYarnProgram](/api/csharp/yarn.unity.yarnproject.compiledyarnprogram.md)||
|[localizations](/api/csharp/yarn.unity.yarnproject.localizations.md)||
|[searchAssembliesForActions](/api/csharp/yarn.unity.yarnproject.searchassembliesforactions.md)|The names of assemblies that  <code>Yarn.Unity.ActionManager</code>  should look for commands and functions in when this project is loaded into a <a href="yarn.unity.dialoguerunner.md">DialogueRunner</a> .|

## Methods

|Name|Description|
|:---|:---|
|[GetLocalization(string)](/api/csharp/yarn.unity.yarnproject.getlocalization.md)||
|[GetProgram()](/api/csharp/yarn.unity.yarnproject.getprogram.md)|Deserializes a compiled Yarn program from the stored bytes in this object.|

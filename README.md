# DOTweenPlugin-For-AngleStruct
It is a DOTween Plugin that allows you to Tween Angle structures with DOTween.

# Usage

Add the following three source files to your Unity project.
- AngleOptions.cs
- AnglePlugin.cs
- AngleTweenExtensions.cs

```csharp
DOTween.To(AnglePlugin.Instance,
           () => Angle.Zero,
           () => { /* update method */},
           Angle.Round,
           1f);
```

# Requirement
- Unity 2020.2.2f
- DOTween Pro 1.0.244
- UnityUtility(contained)

# Other
Get the latest version of the Angle structure from below.
https://github.com/yutorisan/UnityUtility/blob/develop/UnityUnility/Structs/Angle.cs

For information on how to create a DOTweenPlugin for any object, please refer to the following article. (only Japanese)
https://qiita.com/yutorisan/items/1eaff2322fbe28a9fbcb
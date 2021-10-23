# VisualStudio_codeSnippents

List of c# codeSippents

<!-- List of c# codeSippents -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#Debug">Debug</a></li>
    <li><a href="#CreateAssetMenu">CreateAssetMenu</a></li>
    <li><a href="#Namespace">Namespace</a></li>
    <li><a href="#RequireComponent">RequireComponent</a></li>
    <li><a href="#SerializeField">SerializeField</a></li>
    <li><a href="#Custom Unity Event">Custom Unity Event</a></li>
  </ol>
</details>


## Debug
Shortcut - `De`
```c#
Debug.Log("$msg$");
```

## CreateAssetMenu
Shortcut - `creasset`
```c#
[CreateAssetMenu(fileName = "$name$", menuName = "ScriptableObjects/$name$")]
```

## Namespace
Shortcut - `ns`
```c#
namespace $name$
```

## RequireComponent
Shortcut - `requireComp`
```c#
[RequireComponent(typeof($type$))]
```

## SerializeField
Shortcut - `ser`
```c#
[SerializeField] $type$ $name$;
```

## Custom Unity Event
Shortcut - `uev`
```c#
      //using UnityEngine.Events;
      public UnityEvent_$var$ $name$;
      [System.Serializable] public class UnityEvent_$var$ : UnityEvent<$var$>{}
```


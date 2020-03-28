---
layout: reference
section: learn
title: Create
permalink: /learn/ref/Microsoft.Coyote.SystematicTesting/TestingEngine/Create
---
# TestingEngine.Create method (1 of 8)

Creates a new systematic testing engine.

```csharp
public static TestingEngine Create(Configuration configuration)
```

## See Also

* class [Configuration](../../Microsoft.Coyote/ConfigurationType)
* class [TestingEngine](../TestingEngineType)
* namespace [Microsoft.Coyote.SystematicTesting](../TestingEngineType)
* assembly [Microsoft.Coyote](../../MicrosoftCoyoteAssembly)

---

# TestingEngine.Create method (2 of 8)

Creates a new systematic testing engine.

```csharp
public static TestingEngine Create(Configuration configuration, Action test)
```

## See Also

* class [Configuration](../../Microsoft.Coyote/ConfigurationType)
* class [TestingEngine](../TestingEngineType)
* namespace [Microsoft.Coyote.SystematicTesting](../TestingEngineType)
* assembly [Microsoft.Coyote](../../MicrosoftCoyoteAssembly)

---

# TestingEngine.Create method (3 of 8)

Creates a new systematic testing engine.

```csharp
public static TestingEngine Create(Configuration configuration, Action<IActorRuntime> test)
```

## See Also

* class [Configuration](../../Microsoft.Coyote/ConfigurationType)
* interface [IActorRuntime](../../Microsoft.Coyote.Actors/IActorRuntimeType)
* class [TestingEngine](../TestingEngineType)
* namespace [Microsoft.Coyote.SystematicTesting](../TestingEngineType)
* assembly [Microsoft.Coyote](../../MicrosoftCoyoteAssembly)

---

# TestingEngine.Create method (4 of 8)

Creates a new systematic testing engine.

```csharp
public static TestingEngine Create(Configuration configuration, Action<ICoyoteRuntime> test)
```

## See Also

* class [Configuration](../../Microsoft.Coyote/ConfigurationType)
* interface [ICoyoteRuntime](../../Microsoft.Coyote.Runtime/ICoyoteRuntimeType)
* class [TestingEngine](../TestingEngineType)
* namespace [Microsoft.Coyote.SystematicTesting](../TestingEngineType)
* assembly [Microsoft.Coyote](../../MicrosoftCoyoteAssembly)

---

# TestingEngine.Create method (5 of 8)

Creates a new systematic testing engine.

```csharp
public static TestingEngine Create(Configuration configuration, Assembly assembly)
```

## See Also

* class [Configuration](../../Microsoft.Coyote/ConfigurationType)
* class [TestingEngine](../TestingEngineType)
* namespace [Microsoft.Coyote.SystematicTesting](../TestingEngineType)
* assembly [Microsoft.Coyote](../../MicrosoftCoyoteAssembly)

---

# TestingEngine.Create method (6 of 8)

Creates a new systematic testing engine.

```csharp
public static TestingEngine Create(Configuration configuration, Func<IActorRuntime, Task> test)
```

## See Also

* class [Configuration](../../Microsoft.Coyote/ConfigurationType)
* interface [IActorRuntime](../../Microsoft.Coyote.Actors/IActorRuntimeType)
* class [Task](../../Microsoft.Coyote.Tasks/TaskType)
* class [TestingEngine](../TestingEngineType)
* namespace [Microsoft.Coyote.SystematicTesting](../TestingEngineType)
* assembly [Microsoft.Coyote](../../MicrosoftCoyoteAssembly)

---

# TestingEngine.Create method (7 of 8)

Creates a new systematic testing engine.

```csharp
public static TestingEngine Create(Configuration configuration, Func<ICoyoteRuntime, Task> test)
```

## See Also

* class [Configuration](../../Microsoft.Coyote/ConfigurationType)
* interface [ICoyoteRuntime](../../Microsoft.Coyote.Runtime/ICoyoteRuntimeType)
* class [Task](../../Microsoft.Coyote.Tasks/TaskType)
* class [TestingEngine](../TestingEngineType)
* namespace [Microsoft.Coyote.SystematicTesting](../TestingEngineType)
* assembly [Microsoft.Coyote](../../MicrosoftCoyoteAssembly)

---

# TestingEngine.Create method (8 of 8)

Creates a new systematic testing engine.

```csharp
public static TestingEngine Create(Configuration configuration, Func<Task> test)
```

## See Also

* class [Configuration](../../Microsoft.Coyote/ConfigurationType)
* class [Task](../../Microsoft.Coyote.Tasks/TaskType)
* class [TestingEngine](../TestingEngineType)
* namespace [Microsoft.Coyote.SystematicTesting](../TestingEngineType)
* assembly [Microsoft.Coyote](../../MicrosoftCoyoteAssembly)

<!-- DO NOT EDIT: generated by xmldocmd for Microsoft.Coyote.dll -->
# Windows 8 APIs for .NET Core

<img src="http://i.imgur.com/5dzr6Wi.png" width="30%"/>

## What is this?

If you're:

- creating a .NET Core library,
- want to use platform-specific APIs, and
- targeting Windows 8 or 8.1,

then this project is for you.

## Getting Started

Just add this to your `project.json` file:

```json
"frameworks": {
    "win80": {
        "Target.Windows": "8.0.0"
    }
}
```

Want to target Windows 8.1? Bump the version:

```json
"win81": {
    "Target.Windows": "8.1.0"
}
```

That's it! Then, you can write something like:

```csharp
using System;
using System.Collections.Generic;
using Windows.UI.Xaml;

public class MyApp : Application
{
    public MyApp()
    {
        Console.WriteLine("Hello, world!");
    }
}
```

and have it compile.

## Related Projects

- [Target.WindowsPhone](http://github.com/jamesqo/Target.WindowsPhone) - use Windows Phone APIs from .NET Core
- [Target.WindowsRuntime](http://github.com/jamesqo/Target.WindowsRuntime) - use Universal 8.1 APIs from .NET Core

## License

[MIT](LICENSE)

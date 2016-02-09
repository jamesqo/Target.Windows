# Windows 8 APIs for .NET Core

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
    "netcore45": {
        "Target.Windows": "8.0.0"
    }
}
```

Want to target Windows 8.1? Bump the version:

```json
"netcore451": {
    "Target.Windows": "8.1.0"
}
```

## License

[MIT](LICENSE)

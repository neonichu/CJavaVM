# libjvm Swift package

Allows using `libjvm` in other Swift packages.

## Usage

```swift
let package = Package(
    name: "example",
    dependencies: [
        .Package(url: "https://github.com/neonichu/CJavaVM", majorVersion: 1)
    ]
)
```

# SwiftUI-Introspect (Binary)

Pre-built binary xcframeworks for [SwiftUI-Introspect](https://github.com/siteline/SwiftUI-Introspect).

## Usage

Update your package dependency in `Package.swift`:

```swift
// Before (builds from source)
.package(url: "https://github.com/siteline/SwiftUI-Introspect", from: "26.0.0")

// After (uses pre-built binaries)
.package(url: "https://github.com/swift-bins/SwiftUI-Introspect", from: "26.0.0")
```

**Note:** You also need to update your target dependency (package name changes):

```swift
// Before
.product(name: "SwiftUI-Introspect", package: "SwiftUI-Introspect")

// After
.product(name: "SwiftUI-Introspect", package: "siteline_SwiftUI-Introspect")
```

## License

See [LICENSE](LICENSE) - sourced from the original repository.

## Original Repository

For documentation and source code, visit the original repo:
- README: https://github.com/siteline/SwiftUI-Introspect#readme
- Source: https://github.com/siteline/SwiftUI-Introspect

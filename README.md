# simple-debug-version

This package exports a named variable called VERSION of type String

This variable always matches the current version of this package.

```javascript
import {
  VERSION
} from 'simple-debug-version'

// Assuming you installed version 1.0.0
expect(VERSION).to.equal("1.0.0")

// ... Or assuming you installed version 2.0.0
expect(VERSION).to.equal("2.0.0")
```

# What is the purpose of this
Sometimes you want to debug which version of a package is being used by npm.

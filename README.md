# debug-npm-version

This package exports four variables:

 * VERSION
 * MAJOR_VERSION
 * MINOR_VERSION
 * PATCH_VERSION

. These variables always match the current version of this package and are always strings:


```javascript
import {
  VERSION
  MAJOR_VERSION,
  MINOR_VERSION,
  PATCH_VERSION,
} from 'debug-npm-version'

// Assuming version 1.2.0
expect(VERSION).to.equal("1.2.0")
expect(MAJOR_VERSION).to.equal("1")
expect(MINOR_VERSION).to.equal("2")
expect(PATCH_VERSION).to.equal("0")
```

# What is the purpose of this
Sometimes you want to debug which version of a package is being used by npm.

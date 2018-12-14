[![Encapsule Project](https://encapsule.io/images/blue-burst-encapsule.io-icon-72x72.png "Encapsule Project")](https://encapsule.io)

### Encapsule Project

# arccore v0.1.0 "spindrift"

```
Package: arccore v0.1.0 "spindrift" build ID "BpydJRMAQty75quXDPoKMA"
Sources: Encapsule/ARC_master#9684ace298f1f39d83a03255aa16ac913bcddd4e
Purpose: library (Node.js + modern browsers (via package bundler))
Created: 2018-12-14T21:14:04.000Z
License: MIT
```

# Summary

Encapsule Project Addressable Resource Class (ARC) core runtime data modeling and processing libraries.

### arccore.filter

Build self-documenting functions with strong data type and value constraint enforcement provided automatically at runtime.

### arccore.discriminator

Build specialized "discriminator" filter instances that route their incoming `request` to one of N developer-specified filters. Useful for building extensible message processing systems.

### arccore.graph

Directed graph container class and algorithms for modeling and analyzing complex digraph datasets in memory.

### arccore.identifier

Generate non-cryptographic object signatures and random keys in 22-character (128-bit), or 6-character (32-bit) Internet Routable Unique Token (IRUT) string format.

## Distribution

The `arccore` library package is published on [npmjs](https://npmjs.com).

- [arccore Package Distribution](https://npmjs.com/package/arccore/v/0.1.0) ([npm](https://www.npmjs.com/~chrisrus))
- [arccore Package Repository](https://github.com/Encapsule/arccore) ([GitHub](https://github.com/Encapsule))

## Usage

From within your project's root directory...

```
$ npm install arccore --save-dev
```

... or if you use `yarn`:

```
$ yarn add arccore --dev
```

... to declare and install the `arccore` package as a dependency of your project.

Subsequently, import/require `arccore` into module scope as follows:

```JavaScript
const arccore = require('arccore');
```

<hr>

Copyright &copy; 2018 [Christopher D. Russell](http://chrisrussell.net)

Published by [Encapsule Project](https://encapsule.io) Seattle, WA USA
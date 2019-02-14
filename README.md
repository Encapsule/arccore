[![Encapsule Project](https://encapsule.io/images/blue-burst-encapsule.io-icon-72x72.png "Encapsule Project")](https://encapsule.io)

### Encapsule

# arccore v0.1.2 "spindrift2"

```
Package: arccore v0.1.2 "spindrift2" build ID "vUw9VQLQRg-kvku0tlZ-Mw"
Sources: Encapsule/ARC_master#86b4896237eca309f48945204241c4ff0010bc33
Purpose: library (Node.js + modern browsers (via package bundler))
Created: 2019-02-14T18:55:38.000Z
License: MIT
```

# Summary

Encapsule Project Addressable Resource Class (ARC) core runtime data modeling and processing libraries.

## Usage

This package's contained library functionality is intended for use in derived projects.

For example:

1. Create simple test project, declare a dependency and install `arccore` package:

```
$ mkdir testProject && cd testProject
$ yarn init
$ yarn add arccore --dev
```

2. Create a simple script `index.js`:

```JavaScript
const arccore = require('arccore');
console.log(JSON.stringify(arccore.__meta));
/* ... your derived code here ... */
```

## Distribution

The `arccore` library package is published on [npmjs](https://npmjs.com).

- [arccore Package Distribution](https://npmjs.com/package/arccore/v/0.1.2) ([npm](https://www.npmjs.com/~chrisrus))
- [arccore Package Repository](https://github.com/Encapsule/arccore) ([GitHub](https://github.com/Encapsule))

## Contents

Please visit [ARCcore Package Documentation](https://encapsule.io/docs/ARCcore) for more information and detailed developer documentation.

The following sections provide a short overview of the libraries contained in the `arccore` package.

### arccore.filter

Build self-documenting functions with strong data type and value constraint enforcement provided automatically at runtime.

### arccore.discriminator

Register a set of arccore.filter intances to create a "discriminator" filter that "routes" calls to a specific filter in the set based on the shape of the request.

### arccore.graph

Directed graph container class and algorithms for modeling and analyzing [directed graph](https://en.wikipedia.org/wiki/Directed_graph) datasets in memory.

### arccore.identifier

Generate non-cryptographic object signatures and random keys in 6-character (32-bit) and 22-character (128-bit) Internet Routable Unique Token (IRUT) string format.

### arccore.types

A collection of functions for testing and comparing the type of in-memory entities.

### arccore.util

A collection of utility functions used primarily by other libraries contained in the arccore package.

<hr>

Copyright &copy; 2019 [Christopher D. Russell](http://chrisrussell.net)

Published by [Encapsule Project](https://encapsule.io) Seattle, WA USA
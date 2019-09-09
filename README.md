[![Encapsule Project](https://encapsule.io/images/blue-burst-encapsule.io-icon-72x72.png "Encapsule Project")](https://encapsule.io)

### Encapsule Project

# @encapsule/arccore v0.1.6 "grasslands"

```
Package: @encapsule/arccore v0.1.6 "grasslands" build ID "0h8D-8DYQR-oBkbutdis-w"
Sources: Encapsule/ARC_master#5d74e2efa5e8facace0f24e93f35fac480ab6319
Purpose: library (Node.js + modern browsers (via package bundler))
Created: 2019-09-09T21:47:57.000Z
License: MIT
```

# Summary

Encapsule Project Addressable Resource Class (ARC) core runtime data modeling and processing libraries.

## Usage

This package's contained library functionality is intended for use in derived projects.

For example:

1. Create simple test project, declare a dependency and install `@encapsule/arccore` package:

```
$ mkdir testProject && cd testProject
$ yarn init
$ yarn add @encapsule/arccore --dev
```

2. Create a simple script `index.js`:

```JavaScript
const arccore = require('@encapsule/arccore');
console.log(JSON.stringify(arccore.__meta));
/* ... your derived code here ... */
```

## Distribution

The `@encapsule/arccore` library package is published on [npmjs](https://npmjs.com).

- [@encapsule/arccore Package Distribution](https://npmjs.com/package/@encapsule/arccore/v/0.1.6) ([npm](https://www.npmjs.com/@encapsule))
- [@encapsule/arccore Package Repository](https://github.com/Encapsule/arccore) ([GitHub](https://github.com/Encapsule))

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
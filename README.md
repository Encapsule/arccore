# [![Encapsule Project](https://encapsule.io/images/blue-burst-encapsule.io-icon-72x72.png "Encapsule Project")](https://encapsule.io) Encapsule Project

## @encapsule/arccore v0.2.01-firestorm

**Encapsule Project Addressable Resource Cell (ARC) core algorithms runtime library package.**

```
Package: @encapsule/arccore v0.2.01-firestorm build nBb0p-4BTIuUMnI0WUVBJQ
Sources: @encapsule/dpmr-arc-core-at#c47e91c198f493d91cf63cb499ea5b2d79878f41
Purpose: library (Node.js + HTML5)
Created: 2021-08-14T05:11:58.000Z
License: MIT
```

# Overview

> **[ARCcore Runtime Documentation](https://encapsule.io/docs/ARCcore)**

The `@encapsule/arccore` package contains runtime algorithms for schematizing, filtering, routing, and modeling strongly-typed in-memory data within Node.js and HTML5 services runtimes implemented in JavaScript.

# Use

Add the `@encapsule/arccore` the runtime library distribution package to your project's `package.json`:

1. Create simple test project, declare a dependency and install `@encapsule/arccore` package:

```
$ mkdir testProject && cd testProject
$ npm init --yes
$ npm install @encapsule/arccore --save-dev
```

2. Create a simple script `index.js`:

```JavaScript
const arccore = require('@encapsule/arccore');
console.log(JSON.stringify(arccore.__meta));
/* ... your derived code here ... */
```

# Runtime Libraries

## ARCcore.filter

> **[ARCcore.filter Documentation](https://encapsule.io/docs/ARCcore/filter)**

Build self-documenting functions with strong data type and value constraint enforcement provided automatically at runtime.

## ARCcore.discriminator

> **[ARCcore.discriminator Documentation](https://encapsule.io/docs/ARCcore/discriminator)**

Register a set of ARCcore.filter intances to create a "discriminator" filter that "routes" calls to a specific filter in the set based on the shape of the request.

## ARCcore.graph

> **[ARCcore.graph Documentation](https://encapsule.io/docs/ARCcore/graph)**

Directed graph container class and algorithms for modeling and analyzing [directed graph](https://en.wikipedia.org/wiki/Directed_graph) datasets in memory.

## ARCcore.identifier

> **[ARCcore.identifier Documentation](https://encapsule.io/docs/ARCcore/identifier)**

Generate non-cryptographic object signatures and random keys in 6-character (32-bit) and 22-character (128-bit) Internet Routable Unique Token (IRUT) string format.

## ARCcore.types

> **[ARCcore.types Documentation](https://encapsule.io/docs/ARCcore/types)**

A collection of functions for testing and comparing the type of in-memory entities.

## ARCcore.util

> **[ARCcore.util Documentation](https://encapsule.io/docs/ARCcore/identifier)**

A collection of utility functions used primarily by other libraries contained in the arccore package.

# Release Notes

## v0.2.01-firestorm

- Rebuild and test on Node.js v16.6.1.
- Update all build and runtime dependency packages to latest versions.

# Sources

- [https://npmjs.com/package/@encapsule/arccore/v/0.2.01](https://npmjs.com/package/@encapsule/arccore/v/0.2.01)
- [https://github.com/Encapsule/arccore](https://github.com/Encapsule/arccore)

<hr>

[![Encapsule Project](https://encapsule.io/images/blue-burst-encapsule.io-icon-72x72.png "Encapsule Project")](https://encapsule.io)

Published under [MIT](./LICENSE) license by [Encapsule Project](https://github.com/Encapsule)

Copyright &copy; 2021 [Chris Russell](https://github.com/ChrisRus)

Updates and releases are Tweeted [@Encapsule](https://twitter.com/Encapsule)

<hr>
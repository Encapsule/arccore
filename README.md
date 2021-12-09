# [![Encapsule Project](https://encapsule.io/images/blue-burst-encapsule.io-icon-72x72.png "Encapsule Project")](https://encapsule.io) Encapsule Project

## @encapsule/arccore v0.3.1-revontulet

_Encapsule Project Addressable Resource Cell (ARC) core algorithms runtime library package._

```
Package: @encapsule/arccore v0.3.1-revontulet build QC57U7mARS2c3-huXDxZow
Sources: @encapsule/dpmr-arc-core-at#ffe04288d9f0f9b3ddd5da8096dce2dcfaa0d992
Purpose: library (Node.js + HTML5)
Created: 2021-12-09T07:54:38.000Z
License: MIT
```

# Overview

> **[ARCcore Runtime Documentation](https://encapsule.io/docs/ARCcore)**

The `@encapsule/arccore` package contains runtime algorithms for schematizing, filtering, routing, and modeling strongly-typed in-memory data within Node.js and HTML5 services runtimes implemented in JavaScript.

# Use

Add the `@encapsule/arccore` package to your Node.js project's `package.json` manifest:

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

# Package Links

- [@encapsule/arccore Package Distribution](https://npmjs.com/package/@encapsule/arccore/v/0.3.1) (npmjs)
- [@encapsule/arccore Package Repo](https://gitlab.com/encapsule/arccore) (GitLab)
- [@encapsule/arccore Package Issues](https://gitlab.com/encapsule/arccore/-/issues) (GitLab)

# [![Encapsule Project](https://encapsule.io/images/blue-burst-encapsule.io-icon-72x72.png "Encapsule Project")](https://encapsule.io) Encapsule Project

Published under [MIT](./LICENSE) license by [Encapsule Project](https://encapsule.io)

Copyright &copy; 2021 Chris Russell

GitLab: [https://gitlab/encapsule](https://gitlab.encapsule)

Twitter: [https://twitter.com/encapsule](https://twitter.com/encapsule)
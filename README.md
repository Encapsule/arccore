# [![Encapsule Project](https://encapsule.io/images/blue-burst-encapsule.io-icon-72x72.png "Encapsule Project")](https://encapsule.io) Encapsule Project

## @encapsule/arccore v0.3.4-lakeserene

**Encapsule Project Addressable Resource Cell (ARC) core algorithms runtime library package.**

```
Package: @encapsule/arccore v0.3.4-lakeserene build kQreCCrLSIuRNxJGWSQ_vw
Sources: @encapsule/dpmr-arc-core-at#60946ad275bcc97d6d7d7710138c8d3ed7137512
Purpose: library (Node.js + HTML5)
Created: 2022-01-02T22:26:43.000Z
License: MIT
```

> [@encapsule/arccore Package Distribution](https://npmjs.com/package/@encapsule/arccore/v/0.3.4) (npmjs)<br/>
> [@encapsule/arccore Package Repo](https://github.com/encapsule/arccore) (GitHub)<br/>
> [@encapsule/arccore Package Issues](https://github.com/encapsule/arccore/issues) (GitHub)

## Overview

> **[ARCcore Runtime Documentation](https://encapsule.io/docs/ARCcore)**

The `@encapsule/arccore` package contains runtime algorithms for schematizing, filtering, routing, and modeling strongly-typed in-memory data with mathematical graphs and JSON-serializable data types for use in Node.js and HTML5 application services implemented in JavaScript.

## Use

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

## Runtime Libraries

### ARCcore.filter

> **[ARCcore.filter Documentation](https://encapsule.io/docs/ARCcore/filter)**

Build self-documenting functions with strong data type and value constraint enforcement provided automatically at runtime.

### ARCcore.discriminator

> **[ARCcore.discriminator Documentation](https://encapsule.io/docs/ARCcore/discriminator)**

Register a set of ARCcore.filter intances to create a "discriminator" filter that "routes" calls to a specific filter in the set based on the shape of the request.

### ARCcore.graph

> **[ARCcore.graph Documentation](https://encapsule.io/docs/ARCcore/graph)**

Directed graph container class and algorithms for modeling and analyzing [directed graph](https://en.wikipedia.org/wiki/Directed_graph) datasets in memory.

### ARCcore.identifier

> **[ARCcore.identifier Documentation](https://encapsule.io/docs/ARCcore/identifier)**

Generate non-cryptographic object signatures and random keys in 6-character (32-bit) and 22-character (128-bit) Internet Routable Unique Token (IRUT) string format.

### ARCcore.types

> **[ARCcore.types Documentation](https://encapsule.io/docs/ARCcore/types)**

A collection of functions for testing and comparing the type of in-memory entities.

### ARCcore.util

> **[ARCcore.util Documentation](https://encapsule.io/docs/ARCcore/identifier)**

A collection of utility functions used primarily by other libraries contained in the arccore package.

## Dependencies

The `@encapsule/arccore` distribution package bundles and contains the **[uuid](https://www.npmjs.com/package/uuid)** and **[murmurhash-js](https://www.npmjs.com/package/murmurhash-js)** npm packages in order to ensure that the package is self-contained, and functions exactly as verified by our suite of 1700+ regression tests.

If your application service needs to leverages either of these bundled packages directly they are exported from `@encapsule/arccore` as `__bundle.uuid` and `__bundle.murmurhash_js`.

# [![Encapsule Project](https://encapsule.io/images/blue-burst-encapsule.io-icon-72x72.png "Encapsule Project")](https://encapsule.io) Encapsule Project

Published under [MIT](./LICENSE) license by [Encapsule Project](https://encapsule.io)

Copyright &copy; 2012-2022 Chris Russell

GitHub: [https://github/encapsule](https://github.encapsule)

Twitter: [https://twitter.com/encapsule](https://twitter.com/encapsule)
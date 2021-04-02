# [![Encapsule Project](https://encapsule.io/images/blue-burst-encapsule.io-icon-72x72.png "Encapsule Project")](https://encapsule.io) Encapsule Project

# @encapsule/arccore v0.1.11 "woodlands"

```
Package: @encapsule/arccore v0.1.11 "woodlands" build ID "q7umH8vtTI2rvSCMCigCQg"
Sources: Encapsule/ARC_master#fc9a90f7f557ac247a068d0490545928688b8f02
Purpose: library (Node.js + modern browsers (via package bundler))
Created: 2021-02-26T14:05:12.000Z
License: MIT
```

# Summary

## Description

This package is a collection of low-level runtime libraries for modeling, filtering, and routing runtime application state data in JavaScript applications.

The @encapsule/arccore package's main consumers are [@encapsule/arccore](https://github.com/Encapsule/ARCtools) and **[@encapsule/holistic](https://github.com/Encapsule/holistic)** (as well as apps and services derived from the @encapsule/holistic app platform distribution).

The moniker **ARC** stands for **A**addressable **R**esource **C**ell (ARC) which is an abstraction related to celluar automata systems modeling and disitributed application state management. @encapsule/arccore is a toolkit for building such systems in JavaScript. These topics are further explored in the derived  [@encapsule/holistic](https://github.com/Encapsule/holistic) platform distribution.

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

- [@encapsule/arccore Package Distribution](https://npmjs.com/package/@encapsule/arccore/v/0.1.11) ([npm](https://www.npmjs.com/@encapsule))
- [@encapsule/arccore Package Repository](https://github.com/Encapsule/arccore) ([GitHub](https://github.com/Encapsule))

## Contents

The sections below provide a brief summary of the runtime library packages included in the @encapsule/arccore distribution package.

Please visit **[ARCcore Package Docs](https://encapsule.io/docs/ARCcore)** for complete @encapsule/arccore API documentation.

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

[![Encapsule Project](https://encapsule.io/images/blue-burst-encapsule.io-icon-72x72.png "Encapsule Project")](https://encapsule.io)

Copyright &copy; 2021 [Christopher D. Russell](https://github.com/ChrisRus) Seattle, Washington USA

Published under [MIT](./LICENSE) license by [Encapsule Project](https://encapsule.io)

Please follow [@Encapsule](https://twitter.com/Encapsule) on Twitter for news and updates.

<hr>
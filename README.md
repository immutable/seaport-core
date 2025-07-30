# Immutable Seaport-Core

A fork of OpenSea/seaport-core to enable the Immutable seaport fork.

## Upstream Management
`main` always tracks the upstream directly. Released Seaport versions are tagged and diffs to enable the Immutable fork are applied on top of these tags from base branches (i.e `1.5.0-base`)

# seaport-core

[![Version][version-badge]][version-link]
[![npm][npm-badge]][npm-link]

This repo contains the core Seaport smart contracts (with no reference contracts, helpers, or tests) and is meant to facilitate building on Seaport without needing to grapple with long compile times or other complications.

For more information on Seaport, see the [main Seaport repo][seaport].

Related repositories:

- [seaport-types][seaport-types]
- [seaport-sol][seaport-sol]

[seaport]: https://github.com/ProjectOpenSea/seaport
[seaport-core]: https://github.com/ProjectOpenSea/seaport-core
[seaport-types]: https://github.com/ProjectOpenSea/seaport-types
[seaport-sol]: https://github.com/ProjectOpenSea/seaport-sol
[version-badge]: https://img.shields.io/github/package-json/v/ProjectOpenSea/seaport-core
[version-link]: https://github.com/ProjectOpenSea/seaport-core/releases
[npm-badge]: https://img.shields.io/npm/v/seaport-core?color=red
[npm-link]: https://www.npmjs.com/package/seaport-core

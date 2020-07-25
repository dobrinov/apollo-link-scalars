# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [2.0.0](https://github.com/eturino/apollo-link-scalars/compare/v0.1.8...v2.0.0) (2020-07-25)


### ⚠ BREAKING CHANGES

* This version of the library won't be compatible with projects using Apollo 2.

### Bug Fixes

* export "makeExecutableSchema" through apollo-link-scalars ([2e98043](https://github.com/eturino/apollo-link-scalars/commit/2e98043d7bb82aa16776c15d4847211a9419f42c))


* upgrade "apollo-link" to provide Apollo clinet version 3 support ([9315c19](https://github.com/eturino/apollo-link-scalars/commit/9315c19a148c18883f135f6ff95f591127e1421e))

### [0.1.8](https://github.com/eturino/apollo-link-scalars/compare/v0.1.7...v0.1.8) (2020-05-12)

### [0.1.7](https://github.com/eturino/apollo-link-scalars/compare/v0.1.6...v0.1.7) (2020-05-12)


### Bug Fixes

* target ES2017 instead of esnext for module, and ES2015 for main ([08a8246](https://github.com/eturino/apollo-link-scalars/commit/08a82460bd39fe59bdf6ae958f83cfb1b6ecd89b))

### [0.1.6](https://github.com/eturino/apollo-link-scalars/compare/v0.1.5...v0.1.6) (2019-12-31)


### Features

* Target es6 environment for better browser support. ([#31](https://github.com/eturino/apollo-link-scalars/issues/31)) ([d202bd7](https://github.com/eturino/apollo-link-scalars/commit/d202bd7909e66c152c4813985905b40dc3dbf051))

### [0.1.5](https://github.com/eturino/apollo-link-scalars/compare/v0.1.4...v0.1.5) (2019-12-22)

### Bug Fixes

* Avoid parsing issues with null/non-null fields: stop producing graphql errors on parsing when a null is encounter on a non-null value. That is not the responsibility of this link, and it clashes with usages of directives like `@skip` [#28](https://github.com/eturino/apollo-link-scalars/pull/28) [#29](https://github.com/eturino/apollo-link-scalars/issues/29)

### [0.1.4](https://github.com/eturino/apollo-link-scalars/compare/v0.1.3...v0.1.4) (2019-12-05)

### Bug Fixes

* Handle null values for optional types [#21](https://github.com/eturino/apollo-link-scalars/pull/21)

### [0.1.3](https://github.com/eturino/apollo-link-scalars/compare/v0.1.2...v0.1.3) (2019-12-04)


### Features

* `removeTypenameFromInputs` option to remove __typename from inputs ([d9a194f](https://github.com/eturino/apollo-link-scalars/commit/d9a194f11bcc1f26b2a6125e366fa812295ebd1d))

### [0.1.2](https://github.com/eturino/apollo-link-scalars/compare/v0.1.1...v0.1.2) (2019-12-04)


### Bug Fixes

* mutate the operation with serialized vars (avoid shallow copy with wrong prototype errors) ([ab9a107](https://github.com/eturino/apollo-link-scalars/commit/ab9a10797c28d84b48ab9fb416f103a0a7ca640c))

### [0.1.1](https://github.com/eturino/apollo-link-scalars/compare/v0.1.0...v0.1.1) (2019-12-02)


### Features

* exporting `isNone` and `mapIfArray` utils ([031a6d1](https://github.com/eturino/apollo-link-scalars/commit/031a6d1612d4ced48b932fc74490f4004e933eb1))

## 0.1.0 (2019-11-30)


### Features

* `validateEnums` + ensure non-nulls ([feaff53](https://github.com/eturino/apollo-link-scalars/commit/feaff53ffdd724b87363c8ea3aac43270646f23a)), closes [#2](https://github.com/eturino/apollo-link-scalars/issues/2) [#7](https://github.com/eturino/apollo-link-scalars/issues/7)
* can parse scalars as result of query root. Uses the scalar type in the schema or functions ([b4348eb](https://github.com/eturino/apollo-link-scalars/commit/b4348eb244def4821a9e9311fef268aa1c6e7a35))
* initial Fragment Unit helpers ([585a845](https://github.com/eturino/apollo-link-scalars/commit/585a84592eb4f6be12383ddbe764546a47f3d16f))
* serializer of nested + don't __typename ([0014120](https://github.com/eturino/apollo-link-scalars/commit/0014120b876d52251bdcb12a935a28d8e8fad27e)), closes [#18](https://github.com/eturino/apollo-link-scalars/issues/18) [#15](https://github.com/eturino/apollo-link-scalars/issues/15)
* serializer of schema input ([86ff601](https://github.com/eturino/apollo-link-scalars/commit/86ff6017bed8cb61eb30ac596c78878e1cf63d42)), closes [#14](https://github.com/eturino/apollo-link-scalars/issues/14)
* support arrays ([bc84fff](https://github.com/eturino/apollo-link-scalars/commit/bc84fff93671354920195851392ed0dbd82c0b0b)), closes [#5](https://github.com/eturino/apollo-link-scalars/issues/5)
* support for nested objects, including in arrays, and arrays inside of objects ([db16c4d](https://github.com/eturino/apollo-link-scalars/commit/db16c4df20969c38c5af0d0ef0c9bb87cabce67e)), closes [#3](https://github.com/eturino/apollo-link-scalars/issues/3)
* test interfaces and unions ([cd5f654](https://github.com/eturino/apollo-link-scalars/commit/cd5f654747a2783f6ee2dcf89ee695edd4091dbb)), closes [#4](https://github.com/eturino/apollo-link-scalars/issues/4)

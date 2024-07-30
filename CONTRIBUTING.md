# Contributing

Thank you for showing an interest in contributing to Eik 🧡

This module is a [shared config for TypeScript](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html#tsconfig-bases). We accept changes that should apply to all repositories in the [eik-lib origanisation](https://github.com/eik-lib).

Exports from this module are handled via the `"files"` property. Configurations should be at the root level so user's `"extends"` field is `@eik/typescript-config/module.json` and so on.

Commits should follow the [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/) format.

A change in configuration is considered a `patch` in [semantic versioning](https://semver.org/). A new export would be a `minor`. Depending on a newer major version of TypeScript would be a `major`.

This repo uses [semantic release](https://github.com/semantic-release/semantic-release) to automate releases whenever changes are merged to the default branch.

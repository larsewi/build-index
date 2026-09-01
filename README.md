# CFEngine Build Module Index

This repository contains the JSON file which the `cfbs` CLI uses to find modules.

## CFEngine Build Repositories

* [build-index](https://github.com/cfengine/build-index) - Index of modules
* [build-website](https://github.com/cfengine/build-website) - Website
* [cfbs](https://github.com/cfengine/cfbs) - Command line client
* [modules](https://github.com/cfengine/modules) - Official modules provided by the CFEngine team
* [module-template](https://github.com/cfengine/build-example) - Template for creating new modules

## Bumping a module version

Use the [Bump module](https://github.com/cfengine/build-index/actions/workflows/bump_module.yml) GitHub Actions workflow to bump a module's version in `cfbs.json`. Run it manually with the module name and which part of the version to increment (`major`, `minor`, `patch`, or `release`). It opens a pull request with the change for review.

## Contribution Tips

* Run `cfbs pretty ./cfbs.json` after editing to ensure proper formatting.

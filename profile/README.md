# allThingsOps Toolbelt 🚀

🚀 Custom CLI tool to automate DevOps, SecOps, MLOps, and DataOps tasks
 - Website with Video and Text based Guides
 - VSCode packages for all branches of Ops
 - Custom VSCode plugins for all Ops branches

<img align="right" src="./docs/assets/release-it.svg?raw=true" height="280">

- Bump version (in e.g. `package.json`)
- [Git commit, tag, push](#git)
- Execute any (test or build) commands using [hooks](#hooks)
- [Create release at GitHub](#github-releases) or [GitLab](#gitlab-releases)
- [Generate changelog](#changelog)
- [Publish to npm](#publish-to-npm)
- [Manage pre-releases](#manage-pre-releases)
- Extend with [plugins](#plugins)
- Release from any [CI/CD environment](./docs/ci.md)

Use release-it for version management and publish to anywhere with its versatile configuration, a powerful plugin
system, and hooks to execute any command you need to test, build, and/or publish your project.

[![Action Status](https://github.com/release-it/release-it/workflows/Cross-OS%20Tests/badge.svg)](https://github.com/release-it/release-it/actions)
[![npm version](https://badge.fury.io/js/release-it.svg)](https://www.npmjs.com/package/release-it)

## Announcement

The latest major version is v15, supporting Node.js 14 and up (as Node.js v12 is EOL). Use release-it v14 for
environments running Node.js v10 and v12. Also see [CHANGELOG.md](./CHANGELOG.md).

## Links

- See [CHANGELOG.md](./CHANGELOG.md) for major/breaking updates, and
  [releases](https://github.com/release-it/release-it/releases) for a detailed version history.
- To **contribute**, please read [CONTRIBUTING.md](./.github/CONTRIBUTING.md) first.
- Please [open an issue](https://github.com/release-it/release-it/issues/new) if anything is missing or unclear in this
  documentation.

## Installation

Although release-it is a **generic** release tool, most projects use it for projects with npm packages. The recommended
way to install release-it uses npm and adds some minimal configuration to get started:

```bash
npm install ato-cli -g
```


## License

[MIT](./LICENSE)

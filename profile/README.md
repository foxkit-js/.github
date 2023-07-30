# Foxkit

Foxkit is a project by [Mitsunee](https://github.com/Mitsunee) to help speed up development with utility packages, shareable configs and documentation.

<p align="center"><img src="profile/assets/icon-192.png" alt="Foxkit"></p>

Follow us on Mastodon at [@foxkit@fosstodon.org](https://fosstodon.org/@foxkit)

## Projects

After previous experiments with a [monorepo] the project is moving back to the github org. All older repositories have been archived and projects will be migrated one-by-one. Some of the foxkit packages will receive full rewrites with many breaking changes. Here is an overview of migrated projects:

### eslint-config-foxkit

[eslint-config-foxkit](https://github.com/foxkit-js/eslint-config-foxkit) is a set of configuration helpers and rulesets for ESLint. The currently published version can be found in the [monorepo]. Starting with v3.0 we will migrate to ESLint 9-compatible Flat Configs.

### Foxkit List
[Foxkit List](https://github.com/foxkit-js/list) is a Doubly-linked List datastructure for JavaScript and TypeScript. It's main advantage over Arrays is faster insertion times at the start or anywhere inbetween the list, where an Array would have to regenerate its index.

### library-template

The [Foxkit Library Template](https://github.com/foxkit-js/library-template) is a template repository with a complete setup for dual-published npm packages with TypeScript support and pre-configured tooling like ESlint, Prettier (with git hooks), clean-publish and Github Actions.

[monorepo]: https://github.com/Mitsunee/foxkit
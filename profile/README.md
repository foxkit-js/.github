# Foxkit

Foxkit is a project by [Mitsunee](https://github.com/Mitsunee) to help speed up development with utility packages, shareable configs and documentation.

<p align="center"><img src="./assets/icon-192.png" alt="Foxkit"></p>

## Projects

### Library Template

The [Foxkit Library Template](https://github.com/foxkit-js/library-template) is a template repository with a complete setup for dual-published npm packages with TypeScript support and pre-configured tooling like ESlint, Prettier (with git hooks), clean-publish and Github Actions.

### ESLint Configs

We currently offer two base configurations for ESLint (both supporting 8.57.0 and 9.x+): [eslint-config-foxkit](https://github.com/foxkit-js/eslint-config-foxkit) configures slightly modified and expanded base configurations for JavaScript and TypeScript development. [eslint-config-foxkit-react](https://github.com/foxkit-js/eslint-config-foxkit-react) adds support for JSX and React (and Preact!) and can also be used with meta-frameworks such as Astro!

### Util packages

A small collection of helper function for JavaScript and TypeScript development can be found it the Utils package. Currently still found in the [monorepo](https://github.com/Mitsunee/foxkit/tree/main/packages/util).

To help with development on Node.js the [Node Utils](https://github.com/foxkit-js/node-util) package contains a variety of helper functions simplifying Node's API and providing some new features.

### Foxkit List

[Foxkit List](https://github.com/foxkit-js/list) is a Doubly-linked List datastructure for JavaScript and TypeScript. It's main advantage over Arrays is faster insertion times at the start or anywhere inbetween the list, where an Array would have to regenerate its index.

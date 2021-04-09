# ESLint Config for Node.js

ESLint Configuration for Node.js development, with the following parameters,

- Javascript style to support highly readable code
- 120 character lines
- Current ECMAScript (ES20xx) features
- ES Modules using native Node.js ESM syntax
- Type support using JSDoc

## Usage

This configuration is suitable for use with projects that are using ESM (ECMAScript modules), and adding type support using JSDoc conventions. This
allows creating deployment ready Javascript (no transpiling required) that
is supported with rich linting and type-checking tooling.

Type-checking is supported through a combination of ESLint, code editor features
(e.g. VSCode Intellisense), and type-checking tools (e.g. using the Typescript
compiler as a type-checker, but not as a transpiler).

## Acknowledgements

[*ESLint*](https://eslint.org) for the excellent tooling and documentation.

*AirBnb* for the base configuration and reasoning for configuration options.
[GitHub Repo](https://github.com/airbnb/javascript)

The contributors to the ESLint plugin for imports and JSDoc.

## License

MIT

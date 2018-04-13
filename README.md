# esnext-generator [![Build Status](https://travis-ci.org/SimonJang/generator-ts-node.svg?branch=master)](https://travis-ci.org/SimonJang/generator-ts-node)

A `Yeoman` generator to scaffold a Typescript powered node module

# Setup

```
yo ts-node
```

# Lint

- Runs `tslint`.
- Uses the `tslint-xo` extension.

```
npm run lint
```

# Compile

- Compiles your Typescript code
- Moves the `.js` files to a `/dist` folder

```
npm run compile
```

# Test

- Runs the tests
- Runs the `test.js` file with `ava`

```
npm test
```

# TensorFlow.js Examples

This repository contains a set of examples implemented in
[TensorFlow.js](http://js.tensorflow.org).

Each example directory is standalone so the directory can be copied
to another project.


# Dependencies

Except for `getting_started`, all the examples require the following dependencies to be installed.

 - Node.js version 8.9 or higher
 - [NPM cli](https://docs.npmjs.com/cli/npm) OR [Yarn](https://yarnpkg.com/en/)

## How to build an example
`cd` into the directory

If you are using `yarn`:

```sh
cd webcam-transfer-learning/
yarn
yarn watch
```

If you are using `npm`:
```sh
cd webcam-transfer-learning/
npm install
npm run watch
```

### Details

The convention is that each example contains two scripts:

- `yarn watch` or `npm run watch`: starts a local development HTTP server which watches the
filesystem for changes so you can edit the code (JS or HTML) and see changes when you refresh the page immediately.

- `yarn build` or `npm run build`: generates a `dist/` folder which contains the build artifacts and
can be used for deployment.

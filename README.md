# electron-webpack-react-barebones

> A bare minimum project structure to get started developing with [`electron-webpack`](https://github.com/electron-userland/electron-webpack) and [`react`](https://github.com/facebook/react/).

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app),
and combined with [electron-webpack-quick-start](https://github.com/electron-userland/electron-webpack-quick-start).

Thanks to the power of `electron-webpack` this template comes packed with...

- Use of [`webpack-dev-server`](https://github.com/webpack/webpack-dev-server) for development
- HMR for both `renderer` and `main` processes
- Use of [`babel-preset-env`](https://github.com/babel/babel-preset-env) that is automatically configured based on your `electron` version
- Use of [`electron-builder`](https://github.com/electron-userland/electron-builder) to package and build a distributable electron application

Make sure to check out [`electron-webpack`'s documentation](https://webpack.electron.build/) for more details.

## Getting Started

Simply clone this repository, install dependencies, and get started on your application.

The use of the [yarn](https://yarnpkg.com/) package manager is **strongly** recommended, as opposed to using `npm`.

```bash

# copy template using git clone
git clone https://github.com/dankNecessities/electron-webpack-react-barebones.git
cd electron-webpack-react-barebones
rm -rf .git

# install dependencies
yarn
```

### Development Scripts

```bash
# run application in development mode
yarn dev

# compile source code and create webpack output
yarn compile

# `yarn compile` & create build with electron-builder
yarn dist

# `yarn compile` & create unpacked build with electron-builder
yarn dist:dir
```

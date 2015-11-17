# simple-react-webpack-es2015-demo

## Goal of this demo

This demo is going to show how to set up a ReactJS application in ES2015 with webpack.


## Prerequisites

* You know requireJS or something similiar
* You know ES2015 and [Babel](https://babeljs.io/)
* You know something about [ReactJS](https://facebook.github.io/react/)

## How to run

* [webpack](http://webpack.github.io/docs/what-is-webpack.html) -> moudle bundler
* Babel -> transpiles the code into standard ES5 code that can run in older JavaScript environments

install packages with npm:

```bash
npm install --save babel-core babel-loader babel-preset-es2015 babel-preset-react react react-dom webpack webpack-dev-server
```
## Commands:

Build for development:

```bash
webpack
```
Build for production:

```bash
webpack -p
```

Build for continuous incremental build in development:

```bash
webpack --watch
```

Run webpack server:

```bash
webpack-dev-server --progress --colors
```

## How to visit

open [http://localhost:8080/webpack-dev-server/](http://localhost:8080/webpack-dev-server/)

## Additional resources

I refered to [Pete Hunt](https://github.com/petehunt)'s [webpack-how-to](https://github.com/petehunt/webpack-howto) to build this application, hope that can be helpful to you.
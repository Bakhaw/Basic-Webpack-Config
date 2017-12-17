# Basic Webpack Config

## Start with

```
$ yarn init

$ yarn add react react-dom

$ yarn add -D babel-core babel-loader babel-preset-env babel-preset-react babel-plugin-transform-class-properties css-loader style-loader
webpack webpack-dev-server
```

## Add the following scripts

```
"scripts": {
  "build": "webpack",
  "start": "webpack-dev-server --content-base dist/ --open --inline --hot"
}
```

## Finally, run

```
$ yarn build
$ yarn start
```

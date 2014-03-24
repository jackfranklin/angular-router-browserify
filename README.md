# Angular Router Browserify

I'm enjoying working with Angular using Browserify, but couldn't find the angular-route module in a state where I could easily install it and use with with Angular, so I grabbed the source and quickly threw this together.

## Current angular-router version: 1.2.15

## Usage

```
$ npm install --save angular-router-browserify

```js
var angular = require('angular');
require('angular-router-browserify')(angular)

var app = angular.module('myApp', ['ngRoute']);
```

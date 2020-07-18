# Cartridge Lib lodash

[![Version](https://img.shields.io/npm/v/cartridge_lib_lodash.svg)](https://npmjs.org/package/cartridge_lib_lodash)
[![Build Status](https://img.shields.io/travis/pikamachu/pika-cartridge-lib-lodash/master.svg)](https://travis-ci.com/pikamachu/pika-cartridge-lib-lodash)
[![codecov](https://codecov.io/gh/pikamachu/pika-cartridge-lib-lodash/branch/master/graph/badge.svg)](https://codecov.io/gh/pikamachu/pika-cartridge-lib-lodash)

## Introduction

Cartridge library from [lodash](https://www.npmjs.com/package/lodash) npm node module version 3.10.1

... Work in progress ...

## Build with

* [lodash](https://www.npmjs.com/package/lodash)

## Installation

This library can be installed as a standard SFRA cartridge cloning the repository and running npm script uploadCartridge

````
git clone git@github.com:pikamachu/pika-cartridge-lib-lodash.git
cd pika-cartridge-lib-lodash
npm run uploadCartridge
````

Or can be added as a node module dependency to an existing SFRA cartridges project using

````
npm i cartridge_lib_lodash
````

## Usage

This cartridge library is a babel transpilation to ES5 with some minor changes in order to be usable as a standard SFRA cartridge.

Lodash modules can be loaded using require cartridge as a standard SFRA script.

````
// lodash modules can be loaded separately using
var _array = require('*/cartridge/scripts/lib/lodash/array');
var _chain = require('*/cartridge/scripts/lib/lodash/chain');
var _collection = require('*/cartridge/scripts/lib/lodash/collection');
...
````

See [lodash docs](https://lodash.com/docs/3.10.1) documentation for module usage.

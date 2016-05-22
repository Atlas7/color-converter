A mini exercise illustrating TDD (Test Driven Development) / BDD (Behaviour Driven Development) with NodeJS, Mocha, and Chai.

Inspired by [this tutorial](https://semaphoreci.com/community/tutorials/getting-started-with-node-js-and-mocha) by semaphoreci.

# Instruction

Git clone this repository.

Navigate into the root of the repository.

Install all node modules dependencies:

```
npm install
```

To start node server:

```
node app/server.js
```

To perform test:

```
npm test
```

# What the app does

Convert from RGB color code to Hexadecimal string like this (via browser):

```
http://localhost:3000/rgbToHex?red=255&green=255&blue=255
```

Convert from Hexadecimal string to RGB color code like this (via browser):

```
http://localhost:3000/hexToRgb?hex=00ff00
```
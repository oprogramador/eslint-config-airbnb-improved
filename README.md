# eslint-config-airbnb-improved

[![MIT License](https://img.shields.io/badge/license-mit-green.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![node:?](https://img.shields.io/badge/node-%3E=8-blue.svg?style=flat-square)](https://npmjs.org/package/eslint-config-airbnb-improved)
[![Build Status](https://travis-ci.org/oprogramador/eslint-config-airbnb-improved.svg?branch=master)](https://travis-ci.org/oprogramador/eslint-config-airbnb-improved)

[![NPM status](https://nodei.co/npm/eslint-config-airbnb-improved.png?downloads=true&stars=true)](https://npmjs.org/package/eslint-config-airbnb-improved)

Eslint plugin based on [Airbnb](https://github.com/airbnb/javascript)

## install

`npm install --save-dev eslint-config-airbnb-improved`

## usage

in `.eslinrc`:
```json
{
  "extends": "eslint-config-airbnb-improved"
}
```
Of course, you can overwrite any rules to satisfy your needs.

in `package.json`:
```json
{
  "scripts": {
    "lint": "eslint *.js app src",
  }
}
```

run `npm run lint`

## Major differences with standard Airbnb:
- Required sorting of imports and keys in object
- Required empty line before `return`
- Allowing `++` operator
- Allowing not using `this` keyword in object methods.

## Why this plugin?
- Because some of Airbnb rules make coding harder with no good reason.
- Because Airbnb does not specify many coding rules.

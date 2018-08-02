# escape-string-regexp [![Build Status](https://travis-ci.org/sindresorhus/escape-string-regexp.svg?branch=master)](https://travis-ci.org/sindresorhus/escape-string-regexp) [![GuardRails Staging badge](https://badges.staging.guardrails.io/fictional-tribble/sindresorhus--escape-string-regexp.svg)](https://www.staging.guardrails.io)

> Escape RegExp special characters


## Install

```
$ npm install --save escape-string-regexp
```


## Usage

```js
const escapeStringRegexp = require('escape-string-regexp');

const escapedString = escapeStringRegexp('how much $ for a unicorn?');
//=> 'how much \$ for a unicorn\?'

new RegExp(escapedString);
```


## License

MIT © [Sindre Sorhus](http://sindresorhus.com)

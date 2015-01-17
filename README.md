# require-file [![Build Status](https://travis-ci.org/dfcreative/require-file.svg?branch=master)](https://travis-ci.org/dfcreative/require-file) [![Code Climate](https://codeclimate.com/github/dfcreative/require-file/badges/gpa.svg)](https://codeclimate.com/github/dfcreative/require-file) <a href="UNLICENSE"><img src="http://upload.wikimedia.org/wikipedia/commons/6/62/PD-icon.svg" width="20"/></a>


Require file as a string both in node/browser. Simple wrapper for node [rfile](https://www.npmjs.com/package/rfile), but provides browser-side rfile via synchronous `XMLHttpRequest`.


`$ npm install require-file`

```js
var rfile = require('require-file');
var result;

try {
	result = rfile('./local/path');
}
catch (e) {

}
```

If you need async version, take a look at [browser-request](https://github.com/iriscouch/browser-request).


[![NPM](https://nodei.co/npm/require-file.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/require-file/)
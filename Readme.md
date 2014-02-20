*This repository is a mirror of the [component](http://component.io) module [enyo/md5](http://github.com/enyo/md5). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/enyo-md5`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# MD5

  MD5 algorithm written by Paul Johnston

## Installation

    $ component install enyo/md5

## API

```js
// MD5
md5 = require('md5'); // Hex

md5sum = md5('content');


md5 = require('md5').hex; // Identical
md5B64 = require('md5').b64; // Base 64
md5Any = require('md5').any;

// Hmac
hmac = require('md5').hmac; // Hex
hmac = require('md5').hmac.hex; // Identical
hmacB64 = require('md5').hmac.b64; // Base 64
hmacAny = require('md5').hmac.any;

```

## License

  MIT

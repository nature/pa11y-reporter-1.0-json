
pa11y JSON 1.0 reporter
=======================

A reporter for [pa11y][pa11y] 2.0 which outputs 1.0-style JSON.

[![NPM version][shield-npm]][info-npm]
[![Node.js version support][shield-node]][info-node]
[![Build status][shield-build]][info-build]
[![Dependencies][shield-dependencies]][info-dependencies]
[![GPLv3 licensed][shield-license]][info-license]

```sh
pa11y --reporter 1.0-json nature.com
```


Usage
-----

Install pa11y and pa11y-reporter-1.0-json with [npm][npm]:

```
npm install -g pa11y
npm install -g pa11y-reporter-1.0-json
```

Use the reporter with the `--reporter` flag:

```sh
pa11y --reporter 1.0-json nature.com
```

You'll get the 1.0-style JSON:

```js
{
    "isPerfect": Boolean,
    "count": {
        "total": Number,
        "error": Number,
        "warning": Number,
        "notice": Number
    },
    "results": Array
}
```


Contributing
------------

To contribute to pa11y-reporter-1.0-json, clone this repo locally and commit your code on a separate branch.

Please check that everything works by running the following before opening a pull-request:

```sh
make ci
```


License
-------

pa11y-reporter-1.0-json is licensed under the [Lesser General Public License (LGPL-3.0)][info-license].  
Copyright &copy; 2015, Springer Nature


[npm]: https://www.npmjs.com/
[pa11y]: https://github.com/springernature/pa11y

[info-dependencies]: https://gemnasium.com/springernature/pa11y-reporter-1.0-json
[info-license]: LICENSE
[info-node]: package.json
[info-npm]: https://www.npmjs.com/package/pa11y-reporter-1.0-json
[info-build]: https://travis-ci.org/springernature/pa11y-reporter-1.0-json
[shield-dependencies]: https://img.shields.io/gemnasium/springernature/pa11y-reporter-1.0-json.svg
[shield-license]: https://img.shields.io/badge/license-LGPL%203.0-blue.svg
[shield-node]: https://img.shields.io/node/v/pa11y-reporter-1.0-json.svg?label=node.js%20support
[shield-npm]: https://img.shields.io/npm/v/pa11y-reporter-1.0-json.svg
[shield-build]: https://img.shields.io/travis/springernature/pa11y-reporter-1.0-json/master.svg

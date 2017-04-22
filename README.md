# npmdoc-dnscache

#### api documentation for  [dnscache (v1.0.1)](https://github.com/yahoo/dnscache#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-dnscache.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-dnscache) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-dnscache.svg)](https://travis-ci.org/npmdoc/node-npmdoc-dnscache)

#### dnscache for Node

[![NPM](https://nodei.co/npm/dnscache.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/dnscache)

- [https://npmdoc.github.io/node-npmdoc-dnscache/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-dnscache/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-dnscache/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-dnscache/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-dnscache/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-dnscache/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Vinit Sacheti"
    },
    "bugs": {
        "url": "http://github.com/yahoo/dnscache/issues"
    },
    "dependencies": {
        "asap": "~2.0.3",
        "lodash.clone": "~4.3.2"
    },
    "description": "dnscache for Node",
    "devDependencies": {
        "async": "~1.5.2",
        "istanbul": "~0.4.3",
        "jenkins-mocha": "~2.6.0",
        "jshint": "~2.9.2",
        "yui-lint": "~0.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "42cb2b9bfb5e8fbdfa395aac74e127fc05074d31",
        "tarball": "https://registry.npmjs.org/dnscache/-/dnscache-1.0.1.tgz"
    },
    "gitHead": "3669aafb400a406b00c5af5ed02dd53fdb3f5b9b",
    "homepage": "https://github.com/yahoo/dnscache#readme",
    "keywords": [
        "dnscache",
        "dns"
    ],
    "license": "BSD",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "davglass"
        },
        {
            "name": "drewfolta"
        },
        {
            "name": "sylviom"
        },
        {
            "name": "vsacheti"
        }
    ],
    "name": "dnscache",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/yahoo/dnscache.git"
    },
    "scripts": {
        "posttest": "istanbul check-coverage",
        "pretest": "jshint --config ./node_modules/yui-lint/jshint.json ./lib/ ./test/",
        "test": "jenkins-mocha ./test/*.js"
    },
    "version": "1.0.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# api documentation for  [gulp-data (v1.2.1)](https://github.com/colynb/gulp-data#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-data.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-data) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-data.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-data)
#### Generate a data object from a variety of sources: json, front-matter, databases, promises, anything... and set it to the file object for other plugins to consume.

[![NPM](https://nodei.co/npm/gulp-data.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-data)

- [https://npmdoc.github.io/node-npmdoc-gulp-data/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-data/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-data/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-data/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-data/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-data/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Colyn Brown",
        "url": "https://github.com/colynb"
    },
    "bugs": {
        "url": "https://github.com/colynb/gulp-data/issues"
    },
    "contributors": [
        {
            "name": "Izaak Schroeder",
            "url": "http://www.github.com/izaakschroeder"
        }
    ],
    "dependencies": {
        "gulp-util": "^3.0.7",
        "through2": "^2.0.0",
        "util-extend": "^1.0.1"
    },
    "description": "Generate a data object from a variety of sources: json, front-matter, databases, promises, anything... and set it to the file object for other plugins to consume.",
    "devDependencies": {
        "coveralls": "*",
        "istanbul": "*",
        "jshint": "^2.6.0",
        "mocha": "*",
        "mocha-lcov-reporter": "*",
        "q": "^1.0.1",
        "should": "^7.1.1",
        "vinyl": "^1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "a94b54de7d4f3b8ea1f40ef859749c24578cf12b",
        "tarball": "https://registry.npmjs.org/gulp-data/-/gulp-data-1.2.1.tgz"
    },
    "engines": {
        "node": ">=0.9.0",
        "npm": ">=1.2.10"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "f6e8f176b463de4e979bcb9578024caed96c5273",
    "homepage": "https://github.com/colynb/gulp-data#readme",
    "keywords": [
        "gulpplugin",
        "data",
        "json",
        "gulp"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "colynb"
        }
    ],
    "name": "gulp-data",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/colynb/gulp-data.git"
    },
    "scripts": {
        "pretest": "jshint *.js test/*.js",
        "test": "istanbul test _mocha --report html -- test/*.js"
    },
    "version": "1.2.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

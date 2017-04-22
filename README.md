# npmtest-memoizee

#### basic test coverage for  [memoizee (v0.4.4)](https://github.com/medikoo/memoizee#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-memoizee.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-memoizee) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-memoizee.svg)](https://travis-ci.org/npmtest/node-npmtest-memoizee)

#### Memoize/cache function results

[![NPM](https://nodei.co/npm/memoizee.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/memoizee)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-memoizee/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-memoizee/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-memoizee/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-memoizee/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-memoizee/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-memoizee/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-memoizee/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-memoizee/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-memoizee/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-memoizee/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-memoizee/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-memoizee/build/test-report.html](https://npmtest.github.io/node-npmtest-memoizee/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-memoizee/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-memoizee/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-memoizee/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-memoizee/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-memoizee/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-memoizee/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-memoizee/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-memoizee/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mariusz Nowak",
        "url": "http://www.medikoo.com/"
    },
    "bugs": {
        "url": "https://github.com/medikoo/memoizee/issues"
    },
    "dependencies": {
        "d": "1",
        "es5-ext": "^0.10.13",
        "es6-weak-map": "^2.0.1",
        "event-emitter": "^0.3.4",
        "is-promise": "^2.1",
        "lru-queue": "0.1",
        "next-tick": "1",
        "timers-ext": "0.1"
    },
    "description": "Memoize/cache function results",
    "devDependencies": {
        "plain-promise": "^0.1.1",
        "tad": "^0.2.7",
        "xlint": "^0.2.2",
        "xlint-jslint-medikoo": "^0.1.4"
    },
    "directories": {},
    "dist": {
        "shasum": "ecf4b791a09cd11c970203f80682534730fad78f",
        "tarball": "https://registry.npmjs.org/memoizee/-/memoizee-0.4.4.tgz"
    },
    "gitHead": "98d1eaf6f88f3de6da3309bfb91bddad9a471a1a",
    "homepage": "https://github.com/medikoo/memoizee#readme",
    "keywords": [
        "memoize",
        "memoizer",
        "cache",
        "memoization",
        "memo",
        "memcached",
        "hashing.",
        "storage",
        "caching",
        "memory",
        "gc",
        "weak",
        "garbage",
        "collector",
        "async"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "medikoo"
        }
    ],
    "name": "memoizee",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/medikoo/memoizee.git"
    },
    "scripts": {
        "lint": "npm run lint-medikoo -- --no-cache --no-stream",
        "lint-console": "npm run lint-medikoo -- --watch",
        "lint-medikoo": "xlint --linter=node_modules/xlint-jslint-medikoo/index.js",
        "test": "tad"
    },
    "version": "0.4.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# npmdoc-selectn

#### api documentation for  [selectn (v1.1.2)](https://github.com/wilmoore/selectn.js)  [![npm package](https://img.shields.io/npm/v/npmdoc-selectn.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-selectn) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-selectn.svg)](https://travis-ci.org/npmdoc/node-npmdoc-selectn)

#### Curried property accessor function that resolves deeply-nested object properties via dot/bracket-notation string path while mitigating TypeErrors via friendly and composable API.

[![NPM](https://nodei.co/npm/selectn.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/selectn)

- [https://npmdoc.github.io/node-npmdoc-selectn/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-selectn/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-selectn/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-selectn/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-selectn/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-selectn/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Wil Moore III"
    },
    "bugs": {
        "url": "https://github.com/wilmoore/selectn.js/issues"
    },
    "dependencies": {
        "brackets2dots": "^1.1.0",
        "curry2": "^1.0.0",
        "debug": "^2.5.2",
        "dotsplit.js": "^1.0.3"
    },
    "description": "Curried property accessor function that resolves deeply-nested object properties via dot/bracket-notation string path while mitigating TypeErrors via friendly and composable API.",
    "devDependencies": {
        "browserify-standalone": "^0.3.0",
        "dependency-check": "^2.6.1",
        "fixpack": "^2.2.0",
        "istanbul": "^0.4.2",
        "nodemon": "^1.11.0",
        "standard": "^8.0.0",
        "tap-spec": "^4.1.1",
        "tape": "^4.6.3",
        "tape-catch": "^1.0.4",
        "uglify-js": "^2.7.3",
        "zuul": "^3.11.0"
    },
    "directories": {},
    "dist": {
        "shasum": "fc8acd91df3f45acb01891c6773ae529851d6b17",
        "tarball": "https://registry.npmjs.org/selectn/-/selectn-1.1.2.tgz"
    },
    "gitHead": "b0d099863af22e9d2ba7fd69adff6068e8f08d7f",
    "homepage": "https://github.com/wilmoore/selectn.js",
    "keywords": [
        "Mitigate TypeError",
        "TypeError",
        "TypeErrors",
        "access",
        "accessor",
        "bracket-notation string path",
        "browser",
        "callback",
        "composable",
        "compatible",
        "curried",
        "curry",
        "deep",
        "dot-notation string path",
        "dot/bracket-notation",
        "dot/bracket-notation string path",
        "dref",
        "es3",
        "es3 compatible",
        "functional",
        "functor",
        "higher-order",
        "nested",
        "object",
        "parameter order",
        "path-lookup",
        "pathval",
        "pointfree",
        "predicate",
        "property",
        "property access",
        "property accessor",
        "reach",
        "string path",
        "to-function"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "wilmoore"
        }
    ],
    "name": "selectn",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/wilmoore/selectn.js.git"
    },
    "reveal": true,
    "scripts": {
        "build": "browserify-standalone && uglifyjs $npm_package_name.js > $npm_package_name.min.js",
        "clean": "rimraf $npm_package_name.js $npm_package_name.min.js",
        "cover": "istanbul cover test.js",
        "dependency-check": "dependency-check ./package.json && dependency-check ./package.json --unused --no-dev",
        "dev": "nodemon -x 'npm run test --silent' -e 'js json'",
        "fixpack": "fixpack",
        "postversion": "git push --follow-tags && npm publish",
        "prepublish": "npm run build",
        "pretest:browsers": "npm test",
        "standard": "standard",
        "test": "npm run dependency-check && npm run standard --silent && node test.js | tap-spec",
        "test:browsers": "zuul -- test.js",
        "test:browsers:local": "zuul --local 8080 -- test.js"
    },
    "version": "1.1.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

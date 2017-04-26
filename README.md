# npmtest-seraph

#### basic test coverage for  [seraph (v0.15.2)](https://github.com/brikteknologier/seraph#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-seraph.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-seraph) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-seraph.svg)](https://travis-ci.org/npmtest/node-npmtest-seraph)

#### A thin and familiar layer between node and neo4j's REST api.

[![NPM](https://nodei.co/npm/seraph.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/seraph)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-seraph/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-seraph/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-seraph/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-seraph/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-seraph/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-seraph/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-seraph/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-seraph/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-seraph/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-seraph/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-seraph/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-seraph/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-seraph/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-seraph/build/test-report.html](https://npmtest.github.io/node-npmtest-seraph/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-seraph/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-seraph/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-seraph/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-seraph/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-seraph/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-seraph/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-seraph/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-seraph/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "BRIK Teknologier",
        "url": "http://www.brik.no"
    },
    "bugs": {
        "url": "https://github.com/brikteknologier/seraph/issues"
    },
    "contributors": [
        {
            "name": "Jon Packer"
        },
        {
            "name": "Helge Holm"
        },
        {
            "name": "Magnus Hoff"
        }
    ],
    "dependencies": {
        "ascallback": "^1.1.0",
        "async": "~0.2.9",
        "naan": "~1.3.11",
        "neo4j-driver": "^1.1.0-M01",
        "request": "^2.36.0",
        "seraph-core": "^1.1.0",
        "thunkify": "^2.1.2",
        "underscore": "^1.8.3"
    },
    "description": "A thin and familiar layer between node and neo4j's REST api.",
    "devDependencies": {
        "disposable-seraph": "^0.5.1",
        "mocha": "^2.5.3"
    },
    "directories": {},
    "dist": {
        "shasum": "45d56407f3b81c49b24f8f52ccef59bf7de86b06",
        "tarball": "https://registry.npmjs.org/seraph/-/seraph-0.15.2.tgz"
    },
    "gitHead": "3f9f1c3be3c17ac7495f398f214d3720520076b4",
    "homepage": "https://github.com/brikteknologier/seraph#readme",
    "license": "MIT",
    "main": "lib/seraph.js",
    "maintainers": [
        {
            "name": "jonpacker"
        },
        {
            "name": "maghoff"
        }
    ],
    "name": "seraph",
    "optionalDependencies": {},
    "repository": {
        "url": "git+https://github.com/brikteknologier/seraph.git"
    },
    "scripts": {
        "bolt-test": "TEST_MODE=bolt mocha -R spec -t 300000 -b test/root.js test/node.js test/relationship.js test/query.js test/label.js test/batching.js",
        "quick-test": "USE_DIRTY_DATABASE=true NO_STOP=true ./node_modules/mocha/bin/mocha -R spec -t 3000 -s 2000",
        "test": "./node_modules/mocha/bin/mocha -R spec -t 10000 -s 2000"
    },
    "version": "0.15.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

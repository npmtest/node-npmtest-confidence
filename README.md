# npmtest-confidence

#### basic test coverage for  [confidence (v3.0.2)](https://github.com/hapijs/confidence#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-confidence.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-confidence) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-confidence.svg)](https://travis-ci.org/npmtest/node-npmtest-confidence)

#### Configuration API

[![NPM](https://nodei.co/npm/confidence.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/confidence)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-confidence/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-confidence/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-confidence/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-confidence/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-confidence/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-confidence/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-confidence/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-confidence/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-confidence/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-confidence/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-confidence/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-confidence/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-confidence/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-confidence/build/test-report.html](https://npmtest.github.io/node-npmtest-confidence/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-confidence/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-confidence/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-confidence/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-confidence/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-confidence/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-confidence/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-confidence/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-confidence/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "confidence": "bin/confidence"
    },
    "bugs": {
        "url": "https://github.com/hapijs/confidence/issues"
    },
    "dependencies": {
        "alce": "1.x.x",
        "boom": "3.x.x",
        "hoek": "4.x.x",
        "yargs": "4.x.x"
    },
    "description": "Configuration API",
    "devDependencies": {
        "code": "3.x.x",
        "lab": "10.x.x"
    },
    "directories": {},
    "dist": {
        "shasum": "d1cd29994e3b7bc3f69300f87f5bc265c5335e50",
        "tarball": "https://registry.npmjs.org/confidence/-/confidence-3.0.2.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "349f34cd4fbf23a1dd2e272df12fa75dcf794cf7",
    "homepage": "https://github.com/hapijs/confidence#readme",
    "keywords": [
        "hapi",
        "plugin",
        "configuration",
        "api"
    ],
    "licenses": [
        {
            "type": "BSD",
            "url": "http://github.com/hapijs/confidence/raw/master/LICENSE"
        }
    ],
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "hueniverse"
        },
        {
            "name": "wyatt"
        },
        {
            "name": "kpdecker"
        },
        {
            "name": "patrickkettner"
        }
    ],
    "name": "confidence",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/hapijs/confidence.git"
    },
    "scripts": {
        "test": "lab -r console -t 100 -a code -L",
        "test-cov-html": "lab -r html -o coverage.html -a code -L"
    },
    "version": "3.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

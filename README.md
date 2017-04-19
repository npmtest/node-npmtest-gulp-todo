# npmtest-gulp-todo

#### test coverage for  [gulp-todo (v5.3.0)](https://github.com/pgilad/gulp-todo#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-todo.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-todo) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-todo.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-todo)

#### Generate a TODO.md file from comments of files in stream

[![NPM](https://nodei.co/npm/gulp-todo.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-todo)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-todo/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-todo/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-todo/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-todo/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-todo/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-todo/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-todo/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-todo/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-todo/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-todo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-todo/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-todo/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-todo/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-todo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-todo/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-todo/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-todo/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-todo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-todo/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-todo/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-todo/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Gilad Peleg",
        "url": "http://giladpeleg.com"
    },
    "bugs": {
        "url": "https://github.com/pgilad/gulp-todo/issues"
    },
    "dependencies": {
        "gulp-util": "^3.0.7",
        "leasot": "^4.3.0",
        "lodash.defaults": "^4.2.0",
        "lodash.omit": "^4.5.0",
        "through2": "^2.0.3"
    },
    "description": "Generate a TODO.md file from comments of files in stream",
    "devDependencies": {
        "gulp": "^3.9.0",
        "gulp-header": "^1.7.1",
        "gulp-wrap": "^0.13.0",
        "mocha": "^3.2.0",
        "should": "^11.1.2"
    },
    "directories": {},
    "dist": {
        "shasum": "8ca05678078b40efeb739975ae42cb7f7cd315bd",
        "tarball": "https://registry.npmjs.org/gulp-todo/-/gulp-todo-5.3.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "index.js",
        "lib"
    ],
    "gitHead": "1f0cec1715cdbd0935dc2664a68af1f03b0c08dd",
    "homepage": "https://github.com/pgilad/gulp-todo#readme",
    "keywords": [
        "gulpplugin",
        "gulp",
        "js",
        "fixme",
        "comments",
        "todo",
        "list",
        "parse",
        "generator",
        "ci"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "pgilad"
        }
    ],
    "name": "gulp-todo",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/pgilad/gulp-todo.git"
    },
    "scripts": {
        "test": "mocha -R spec tests/*.js",
        "watchTest": "mocha --watch -R spec tests/*.js"
    },
    "version": "5.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

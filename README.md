# test coverage for  [flightplan (v0.6.15)](https://github.com/pstadler/flightplan)  [![npm package](https://img.shields.io/npm/v/npmtest-flightplan.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-flightplan) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-flightplan.svg)](https://travis-ci.org/npmtest/node-npmtest-flightplan)
#### Library for streamlining application deployment or systems administration tasks

[![NPM](https://nodei.co/npm/flightplan.png?downloads=true)](https://www.npmjs.com/package/flightplan)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-flightplan/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-flightplan/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-flightplan/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-flightplan/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-flightplan/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-flightplan/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-flightplan/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-flightplan/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-flightplan/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-flightplan/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-flightplan%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-flightplan/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-flightplan/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-flightplan%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-flightplan/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-flightplan/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-flightplan/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Patrick Stadler",
        "email": "patrick.stadler@gmail.com"
    },
    "bin": {
        "fly": "./bin/fly.js"
    },
    "bugs": {
        "url": "https://github.com/pstadler/flightplan/issues"
    },
    "dependencies": {
        "byline": "^4.2.1",
        "chalk": "^1.1.1",
        "fibers": "^1.0.10",
        "interpret": "^1.0.0",
        "liftoff": "^2.2.0",
        "nopt": "^3.0.4",
        "pretty-hrtime": "^1.0.1",
        "prompt": "^0.2.14",
        "semver": "^5.1.0",
        "ssh2": "^0.4.15",
        "util-extend": "^1.0.1",
        "v8flags": "^2.0.10"
    },
    "description": "Library for streamlining application deployment or systems administration tasks",
    "devDependencies": {
        "chai": "^3.3.0",
        "coveralls": "^2.11.4",
        "eslint": "^1.10.3",
        "istanbul": "^0.4.0",
        "markdox": "^0.1.10",
        "mocha": "^2.3.3",
        "pre-commit": "^1.1.1",
        "proxyquire": "^1.7.3",
        "sinon": "^1.17.2"
    },
    "directories": {},
    "dist": {
        "shasum": "f8dff79554a02daff87f1c584aaf7ac7477c846c",
        "tarball": "https://registry.npmjs.org/flightplan/-/flightplan-0.6.15.tgz"
    },
    "gitHead": "9e04ecf71677222b7d8460ffffbcac9b30f51b45",
    "homepage": "https://github.com/pstadler/flightplan",
    "keywords": [
        "deploy",
        "deployment",
        "commands",
        "devops",
        "exec",
        "shell",
        "bash",
        "ssh",
        "tasks",
        "parallel",
        "sequential",
        "remote",
        "local",
        "cloud",
        "fabric"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "pstadler",
            "email": "patrick.stadler@gmail.com"
        }
    ],
    "name": "flightplan",
    "optionalDependencies": {},
    "pre-commit": [
        "lint"
    ],
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/pstadler/flightplan.git"
    },
    "scripts": {
        "coverage": "rm -rf ./coverage; ./node_modules/.bin/istanbul cover --dir coverage/lib ./node_modules/.bin/_mocha -- -R spec; ./node_modules/.bin/istanbul report",
        "coverage-lcov": "rm -rf ./coverage; ./node_modules/.bin/istanbul cover --dir coverage/lib --report lcovonly ./node_modules/.bin/_mocha -- -R spec; ./node_modules/.bin/istanbul report lcovonly",
        "coveralls": "npm run coverage-lcov && cat ./coverage/lcov.info | ./node_modules/.bin/coveralls",
        "docs": "cd ./docs; node generate.js",
        "lint": "eslint .",
        "test": "mocha"
    },
    "version": "0.6.15"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

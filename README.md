# test coverage for  [pm2-gui (v0.1.4)](https://github.com/Tjatse/pm2-gui)  [![npm package](https://img.shields.io/npm/v/npmtest-pm2-gui.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pm2-gui) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pm2-gui.svg)](https://travis-ci.org/npmtest/node-npmtest-pm2-gui)
#### An elegant web & terminal interface for Unitech/PM2.

[![NPM](https://nodei.co/npm/pm2-gui.png?downloads=true)](https://www.npmjs.com/package/pm2-gui)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pm2-gui/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pm2-gui/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pm2-gui/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pm2-gui/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pm2-gui/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pm2-gui/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pm2-gui/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pm2-gui/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-pm2-gui/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-pm2-gui/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-pm2-gui%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pm2-gui/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pm2-gui/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-pm2-gui%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pm2-gui/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pm2-gui/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pm2-gui/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tjatse"
    },
    "bin": {
        "pm2-gui": "./pm2-gui"
    },
    "bugs": {
        "url": "https://github.com/Tjatse/pm2-gui/issues"
    },
    "dependencies": {
        "ansi-html": "~0.0.5",
        "async": "~1.5.2",
        "blessed": "^0.1.81",
        "chalk": "~1.1.3",
        "commander": "~2.9.0",
        "express": "~4.13.4",
        "express-session": "~1.13.0",
        "inquirer": "~1.0.2",
        "jade": "~1.11.0",
        "lodash": "~4.12.0",
        "pidusage": "~1.0.1",
        "pm2-axon": "~2.0.11",
        "pm2-axon-rpc": "~0.3.6",
        "socket.io": "~1.4.6",
        "socket.io-client": "~1.4.6",
        "windows-cpu": "~0.1.4"
    },
    "description": "An elegant web & terminal interface for Unitech/PM2.",
    "devDependencies": {
        "standard": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "e4d239249dde02d9f546975a2ee78b134f77d7e6",
        "tarball": "https://registry.npmjs.org/pm2-gui/-/pm2-gui-0.1.4.tgz"
    },
    "engines": [
        "node >= 0.8.0"
    ],
    "gitHead": "b0d670c283d551edccc43c230c8a5554e6e6772d",
    "homepage": "https://github.com/Tjatse/pm2-gui",
    "keywords": [
        "monitor",
        "dashboard",
        "PM2",
        "PM2 interface",
        "PM2 web",
        "PM2 ui",
        "PM2 gui",
        "PM2 dashboard",
        "PM2 monitor"
    ],
    "license": "MIT",
    "main": "./pm2-gui.js",
    "maintainers": [
        {
            "name": "tjatse",
            "email": "thisnamemeansnothing@gmail.com"
        }
    ],
    "name": "pm2-gui",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/Tjatse/pm2-gui.git"
    },
    "scripts": {
        "test": "NODE_ENV=test bash test/index.sh"
    },
    "standard": {
        "ignore": [
            "web/public/"
        ],
        "globals": [
            "action",
            "__route_root"
        ]
    },
    "version": "0.1.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

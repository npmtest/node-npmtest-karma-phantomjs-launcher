# test coverage for  [karma-phantomjs-launcher (v1.0.4)](https://github.com/karma-runner/karma-phantomjs-launcher#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-karma-phantomjs-launcher.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-karma-phantomjs-launcher) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-karma-phantomjs-launcher.svg)](https://travis-ci.org/npmtest/node-npmtest-karma-phantomjs-launcher)
#### A Karma plugin. Launcher for PhantomJS.

[![NPM](https://nodei.co/npm/karma-phantomjs-launcher.png?downloads=true)](https://www.npmjs.com/package/karma-phantomjs-launcher)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-karma-phantomjs-launcher/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-karma-phantomjs-launcher/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-karma-phantomjs-launcher/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-karma-phantomjs-launcher/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-karma-phantomjs-launcher/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-karma-phantomjs-launcher/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-karma-phantomjs-launcher/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-karma-phantomjs-launcher/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-karma-phantomjs-launcher/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-karma-phantomjs-launcher/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-karma-phantomjs-launcher%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-karma-phantomjs-launcher/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-karma-phantomjs-launcher/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-karma-phantomjs-launcher%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-karma-phantomjs-launcher/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-karma-phantomjs-launcher/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-karma-phantomjs-launcher/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Vojta Jina",
        "email": "vojta.jina@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/karma-runner/karma-phantomjs-launcher/issues"
    },
    "contributors": [
        {
            "name": "Vojta Jina",
            "email": "vojta.jina@gmail.com"
        },
        {
            "name": "Friedel Ziegelmayer",
            "email": "dignifiedquire@gmail.com"
        },
        {
            "name": "Mark Ethan Trostler",
            "email": "mark@zzo.com"
        },
        {
            "name": "Shinnosuke Watanabe",
            "email": "snnskwtnb@gmail.com"
        },
        {
            "name": "Jurko Gospodnetić",
            "email": "jurko.gospodnetic@pke.hr"
        },
        {
            "name": "Friedel Ziegelmayer",
            "email": "friedel.ziegelmayer@gmail.com"
        },
        {
            "name": "Sylvain Hamel",
            "email": "sylvainhamel0@gmail.com"
        },
        {
            "name": "Huafu Gandon",
            "email": "huafu.gandon@gmail.com"
        },
        {
            "name": "Dan Siwiec",
            "email": "daniel.siwiec@gmail.com"
        },
        {
            "name": "Rob Barreca",
            "email": "rob.barreca@inmobi.com"
        },
        {
            "name": "Sergey Bondarenko",
            "email": "enterit@gmail.com"
        },
        {
            "name": "nherzing",
            "email": "nherzing@gmail.com"
        },
        {
            "name": "Chad Smith",
            "email": "chad@configit.com"
        },
        {
            "name": "sylvain-hamel",
            "email": "sylvainhamel0@gmail.com"
        },
        {
            "name": "Edward Hutchins",
            "email": "eahutchins@gmail.com"
        },
        {
            "name": "Eryk Napierała",
            "email": "eryk.piast@gmail.com"
        },
        {
            "name": "Jason Dobry",
            "email": "jason.dobry@gmail.com"
        },
        {
            "name": "Joel Mukuthu",
            "email": "jmu@one.com"
        },
        {
            "name": "Jonathan Park",
            "email": "jpark@daptiv.com"
        },
        {
            "name": "Leigh Tarasenko",
            "email": "leightarasenko@gmail.com"
        },
        {
            "name": "Mark Derbecker",
            "email": "mark.derbecker@seeq.com"
        },
        {
            "name": "Mark Trostler",
            "email": "mark@zzo.com"
        },
        {
            "name": "Nick Malaguti",
            "email": "nmalaguti@palantir.com"
        }
    ],
    "dependencies": {
        "lodash": "^4.0.1",
        "phantomjs-prebuilt": "^2.1.7"
    },
    "description": "A Karma plugin. Launcher for PhantomJS.",
    "devDependencies": {
        "eslint": "^1.0.0",
        "eslint-config-standard": "^4.0.0",
        "eslint-plugin-react": "^3.2.0",
        "eslint-plugin-standard": "^1.3.1",
        "grunt": "~0.4.1",
        "grunt-auto-release": "~0.0.2",
        "grunt-bump": "~0.3.1",
        "grunt-conventional-changelog": "^1.2.2",
        "grunt-eslint": "^17.0.0",
        "grunt-karma": "1.x || ^0.12.1",
        "grunt-npm": "~0.0.2",
        "jasmine-core": "^2.3.4",
        "karma": "1.x || ^0.13.6",
        "karma-jasmine": "1.x || ^0.3.5",
        "load-grunt-tasks": "^3.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "d23ca34801bda9863ad318e3bb4bd4062b13acd2",
        "tarball": "https://registry.npmjs.org/karma-phantomjs-launcher/-/karma-phantomjs-launcher-1.0.4.tgz"
    },
    "gitHead": "eb0ca03d1938ed7b18da572284d3d52e2c1b70c9",
    "homepage": "https://github.com/karma-runner/karma-phantomjs-launcher#readme",
    "keywords": [
        "karma-plugin",
        "karma-launcher",
        "phantomjs"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "vojtajina",
            "email": "vojta.jina+npm@gmail.com"
        },
        {
            "name": "zzo",
            "email": "mark@zzo.com"
        },
        {
            "name": "dignifiedquire",
            "email": "dignifiedquire@gmail.com"
        },
        {
            "name": "karmarunnerbot",
            "email": "karmarunnerbot@gmail.com"
        }
    ],
    "name": "karma-phantomjs-launcher",
    "optionalDependencies": {},
    "peerDependencies": {
        "karma": ">=0.9"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/karma-runner/karma-phantomjs-launcher.git"
    },
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "version": "1.0.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

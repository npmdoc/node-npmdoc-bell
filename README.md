# npmdoc-bell

#### api documentation for  bell (v8.6.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-bell.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-bell) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-bell.svg)](https://travis-ci.org/npmdoc/node-npmdoc-bell)

#### Third-party login plugin for hapi

[![NPM](https://nodei.co/npm/bell.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bell)

- [https://npmdoc.github.io/node-npmdoc-bell/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bell/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bell/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bell/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-bell/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-bell/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "bell",
    "description": "Third-party login plugin for hapi",
    "version": "8.6.0",
    "repository": "git://github.com/hapijs/bell",
    "main": "lib/index.js",
    "keywords": [
        "hapi",
        "login",
        "authentication",
        "oauth",
        "plugin",
        "auth0",
        "arcgisonline",
        "bitbucket",
        "dropbox",
        "facebook",
        "fitbit",
        "foursquare",
        "github",
        "gitlab",
        "google",
        "instagram",
        "medium",
        "linkedin",
        "live",
        "meetup",
        "nest",
        "phabricator",
        "office365",
        "okta",
        "reddit",
        "spotify",
        "tumblr",
        "twitter",
        "vk",
        "wordpress",
        "yahoo"
    ],
    "engines": {
        "node": ">=4.0.0"
    },
    "dependencies": {
        "boom": "4.2.x",
        "cryptiles": "3.x.x",
        "hoek": "4.x.x",
        "joi": "10.x.x",
        "wreck": "10.x.x"
    },
    "peerDependencies": {
        "hapi": ">=13.5.0"
    },
    "devDependencies": {
        "hapi": "16.x.x",
        "hawk": "6.x.x",
        "lab": "13.x.x",
        "code": "4.x.x",
        "sinon": "1.x.x"
    },
    "scripts": {
        "test": "node node_modules/lab/bin/lab -t 100 -L -v",
        "test-cov-html": "node node_modules/lab/bin/lab -r html -o coverage.html -L"
    },
    "license": "BSD-3-Clause"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

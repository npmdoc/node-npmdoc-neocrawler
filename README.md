# npmdoc-neocrawler

#### api documentation for  neocrawler (v2.0.2)  [![npm package](https://img.shields.io/npm/v/npmdoc-neocrawler.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-neocrawler) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-neocrawler.svg)](https://travis-ci.org/npmdoc/node-npmdoc-neocrawler)

#### Nodejs Distribute Crawler

[![NPM](https://nodei.co/npm/neocrawler.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/neocrawler)

- [https://npmdoc.github.io/node-npmdoc-neocrawler/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-neocrawler/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-neocrawler/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-neocrawler/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-neocrawler/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-neocrawler/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "neocrawler",
    "description": "Nodejs Distribute Crawler",
    "keywords": [
        "nodejs",
        "crawler",
        "phantomjs"
    ],
    "author": {
        "name": "James",
        "url": "http://my.oschina.net/waterbear/blog"
    },
    "version": "2.0.2",
    "main": "./run.js",
    "bin": {
        "run": "./run.js"
    },
    "repository": {
        "type": "git",
        "url": "http://git.oschina.net/dreamidea/neocrawler.git"
    },
    "dependencies": {
        "log4js": "0.6.9",
        "optimist": "0.6.0",
        "redis": ">=0.12.1",
        "cheerio": "0.12.4",
        "iconv-lite": "0.2.11",
        "bufferhelper": "0.2.0",
        "async": ">=0.2.10",
        "request": "2.33.0",
        "thrift": "0.9.1",
        "hbase": "0.1.6",
        "protobufjs": "^2.2.1",
        "zookeeper-watcher": "^0.2.0",
        "readable-stream": "^1.0.26-4",
        "debug": "^1.0.0",
        "ejs": "0.8.5",
        "express": "3.3.4",
        "stylus": "0.40.3",
        "mysql": "2.0.0",
        "mongodb": ">=1.4.0-rc8",
        "generic-pool": ">=2.1.1"
    },
    "scripts": {
        "start": "node run.js",
        "test": "node test/test.js"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

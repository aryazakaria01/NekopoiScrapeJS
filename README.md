# Nekopoi Scrapper Java Script

*Scrapper for nekopoi*

[![pipeline status](https://gitlab.com/moepoi/NekopoiScrapper/badges/master/pipeline.svg)](https://gitlab.com/moepoi/NekopoiScrapper/-/commits/master)

<a href="https://www.codefactor.io/repository/github/aryazakaria01/nekopoiscrapejs"><img src="https://www.codefactor.io/repository/github/aryazakaria01/nekopoiscrapejs/badge" alt="CodeFactor" /></a>

## Installation

```sh
$ npm install
```

## Usage

```sh
const NekopoiScrapper = require('./NekopoiScrapper');

// Latest Release
NekopoiScrapper.getLatest()
    .then(result => console.log(result))

// Get Page Info
NekopoiScrapper.getInfo("https://nekopoi.care/sexfriend-gakuen-episode-1-subtitle-indonesia/")
    .then(result => console.log(result));
```

## Credit

Arya Zakaria ~ / [Arya Zakaria](https://github.com/aryazakaria01)

## [OWNER Arya](http://t.me/Badboyanim)

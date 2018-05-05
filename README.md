[![Build Status](https://travis-ci.org/Alheimsins/bigfive-web.svg?branch=master)](https://travis-ci.org/Alheimsins/bigfive-web)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://github.com/feross/standard)
[![Greenkeeper badge](https://badges.greenkeeper.io/Alheimsins/bigfive-web.svg)](https://greenkeeper.io/)

# bigfive-web

Website for five factor model of personality based on work from [IPIP-NEO-PI](https://github.com/kholia/IPIP-NEO-PI).

Tests and evaluation is gathered from [ipip.ori.org](http://ipip.ori.org).

See it live @ [bigfive.world](https://bigfive-test.com)

Written in [nodejs](https://nodejs.org) using [next.js](https://github.com/zeit/next.js)- and [micro](https://github.com/zeit/micro) framework

## Installation

Download and install [nodejs](https://nodejs.org) and [git](https://git-scm.com/downloads)

The results are saved to a [mongodb](https://www.mongodb.com/) database, so for a full test you either need a running mongodb or an instance at [mlab](https://mlab.com/)

```sh
git clone https://github.com/Alheimsins/bigfive-web
cd bigfive-web
npm install
vim config.js # Edit config
npm run dev
```
Open web-browser at http://localhost:3000

## Deploy using [Now](https://zeit.co/now)

```sh
$ wget https://raw.githubusercontent.com/Alheimsins/bigfive-web/master/production.env
$ vim production.env # Edit config
$ now -E production.env https://github.com/Alheimsins/bigfive-web
```

## Deploy using [Docker](https://www.docker.com/)

Install [Docker](https://www.docker.com/)

```sh
docker run -d --name bigfive-web alheimsins/bigfive-web
```

## License

[MIT](LICENSE)

## About

Created by [zrrzzt](https://github.com/zrrrzzt) and [maccyber](https://github.com/maccyber) with ❤ for [Alheimsins](https://alheimsins.net)

<img src="https://image.ibb.co/dPH08G/logo_black.png" height="150px" width="150px" />

![Robohash image of zrrrzzt](https://robots.kebabstudios.party/zrrrzzt.png "Robohash image of zrrrzzt")
![Robohash image of maccyber](https://robots.kebabstudios.party/maccyber.png "Robohash image of maccyber")

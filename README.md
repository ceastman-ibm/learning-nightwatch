# learning-nightwatch
> Nightwatch running on a Zalenium container

Requires `docker` installed.

## Zalenium

> A flexible and scalable container based Selenium Grid with video recording, live preview, basic auth & dashboard.

[Click here to know more about Zalenium](https://github.com/zalando/zalenium).

## Install

If `postinstall` did not ran after `npm install`, please run:

```sh
$ docker pull elgalu/selenium
$ docker pull dosel/zalenium
```

## Usage

```sh
$ npm run zalenium:start
$ npm test
$ npm run zalenium:stop
```

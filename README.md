# Wapty (Web Application Penetration Testing Suite)y

[![License](https://img.shields.io/badge/license-GPLv3-blue.svg)](https://raw.githubusercontent.com/empijei/wapty/master/LICENSE)
[![Build Status](https://travis-ci.org/empijei/wapty.svg?branch=master)](https://travis-ci.org/empijei/wapty) 
[![Go Report Card](https://goreportcard.com/badge/github.com/empijei/wapty)](https://goreportcard.com/report/github.com/empijei/wapty)
[![codebeat](https://codebeat.co/badges/9a62559f-ebf7-4097-8023-c8745e73ace8)](https://codebeat.co/projects/github-com-empijei-wapty-master)
[![Telegram Chat](https://img.shields.io/badge/discuss-telegram-179cde.svg?maxAge=3600)](https://telegram.me/waptysuite)
[![Stability](https://img.shields.io/badge/stability-unstable-yellow.svg)](https://github.com/empijei/wapty/blob/master/ROADMAP.md)
[![Changelog](https://img.shields.io/github/release/empijei/wapty.svg?maxAge=2592000)](https://github.com/empijei/wapty/releases)
[![Funding](https://img.shields.io/badge/funding-hobby-lightgrey.svg)](https://github.com/empijei/wapty)

An Open Source alternative to Burp Suite.

We are working to make wapty a worthy replacement for Burp, but we are [not there yet](https://github.com/empijei/wapty/blob/master/ROADMAP.md).
# Usage
```sh
go get github.com/empijei/wapty
cd $GOPATH/src/github.com/empijei/wapty
make installdeps
make
make install
```

on your browser set localhost:8080 as proxy

**_BEWARE_**: ignore proxy for localhost

Then visit localhost:8081

Root certs are in `$HOME/.wapty`

# Project Status
for currently available features and what will be supported please refer to [our roadmap](https://github.com/empijei/wapty/blob/master/ROADMAP.md).

A screenshot:

![intercept](https://github.com/empijei/wapty/raw/master/documentation/screenshot.png)

# Contribute
Pull Requests are welcome, or if you'd like to actively contribute or become part of the team feel free to shoot me a short email of presentation at [empijei@gmail.com](mailto:empijei@gmail.com) or join our [telegram channel](https://telegram.me/waptysuite)

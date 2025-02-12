<h1>
  <img src="https://github.com/iobroker-community-adapters/ioBroker.info/blob/master/admin/info.png" width="64"/>
  ioBroker.info
</h1>

![Number of Installations](http://iobroker.live/badges/info-installed.svg) 
![Number of Installations](http://iobroker.live/badges/info-stable.svg) 
[![NPM version](http://img.shields.io/npm/v/iobroker.info.svg)](https://www.npmjs.com/package/iobroker.info)
[![Downloads](https://img.shields.io/npm/dm/iobroker.info.svg)](https://www.npmjs.com/package/iobroker.info)

[![NPM](https://nodei.co/npm/iobroker.info.png?downloads=true)](https://nodei.co/npm/iobroker.info/)

[![Travis-CI](http://img.shields.io/travis/iobroker-community-adapters/ioBroker.info/master.svg)](https://travis-ci.org/iobroker-community-adapters/ioBroker.info)
[![Greenkeeper badge](https://badges.greenkeeper.io/iobroker-community-adapters/ioBroker.info.svg)](https://greenkeeper.io/)
[![Dependency Status](https://img.shields.io/david/iobroker-community-adapters/iobroker.info.svg)](https://david-dm.org/iobroker-community-adapters/iobroker.info)
[![Known Vulnerabilities](https://snyk.io/test/github/iobroker-community-adapters/ioBroker.info/badge.svg)](https://snyk.io/test/github/iobroker-community-adapters/ioBroker.info)

## Information adapter for ioBroker

This is an ioBroker adapter to get informations about your system and some news about ioBroker.

## Informations

### Forum and News
If you reach your admin window over a hostname (for example, http://myhouseiscontrolledbyioBroker:8081), the news and forum entries will not be automatically displayed. To do this, you must first register your host name [here](https://toolkit.sekando.com/docs/en/setup/hostnames).
After that just enter the API Key in the configuration of the adapter.

### Popup Messages (VIS Widget)
There is a new widget to display important messages in VIS. These messages are displayed ONLY if certain conditions are met. Either from date x to date y or even if you have a specific adapter installed. If nothing is displayed then everything is ok.

## Changelog

### 1.3.x (2019-04-01)
* (ldittmar) better system information

### 1.2.7 (2019-03-17)
* (ldittmar) little fixes
* (ldittmar) unknow adapters search new design
* (ldittmar) better design for PC monitor
* (ldittmar) unknow adapters show more informations
* (ldittmar) stable version

### 1.2.5 (2019-03-14)
* (ldittmar) show adapter requests
* (ldittmar) show bugs and issues
* (ldittmar) diyplay important links
* (ldittmar) show important popup news
* (ldittmar) vis widget for popup news

### 1.1.3 (2019-01-03)
* (ldittmar) compact mode compatibility added
* (ldittmar) add chinese support
* (ldittmar) add new forum support
* (ldittmar) add chinese forum support
* (ldittmar) move to iobroker-community-adapters

### 1.0.2 (2018-11-30)
* (ldittmar) fixed problems with Node version info in multihost system

### 1.0.1 (2018-11-27)
* (ldittmar) search for new adapters on Github
* (ldittmar) check for Node.js update
* (ldittmar) https problems with news and forum data solved
* (ldittmar) polish added as language

### 1.0.0 (2018-11-25)
* (ldittmar) full compatibility to Admin 3.x
* (ldittmar) clock can be disabled

### 0.1.0 (2018-01-02)
* (ldittmar) compatibility to Admin 3.x / beta release

### 0.0.6 (2017-12-11)
* (ldittmar) some fixes / install and update implemented

### 0.0.4 (2017-12-08)
* (ldittmar) some fixes and design correction
* (ldittmar) show informations about adapters (update/new)
* (ldittmar) show system informations

### 0.0.1 (2017-11-23)
* (ldittmar) initial commit

## License
The MIT License (MIT)

Copyright (c) 2017 - 2019 ldittmar <iobroker@lmdsoft.de>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

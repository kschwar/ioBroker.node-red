![Logo](admin/node-red.png)

# ioBroker.node-red

[![NPM version](https://img.shields.io/npm/v/iobroker.node-red?style=flat-square)](https://www.npmjs.com/package/iobroker.node-red)
[![Downloads](https://img.shields.io/npm/dm/iobroker.node-red?label=npm%20downloads&style=flat-square)](https://www.npmjs.com/package/iobroker.node-red)
![node-lts](https://img.shields.io/node/v-lts/iobroker.node-red?style=flat-square)
![Libraries.io dependency status for latest release](https://img.shields.io/librariesio/release/npm/iobroker.node-red?label=npm%20dependencies&style=flat-square)

![GitHub](https://img.shields.io/github/license/iobroker/iobroker.node-red?style=flat-square)
![GitHub repo size](https://img.shields.io/github/repo-size/iobroker/iobroker.node-red?logo=github&style=flat-square)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/iobroker/iobroker.node-red?logo=github&style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/iobroker/iobroker.node-red?logo=github&style=flat-square)
![GitHub issues](https://img.shields.io/github/issues/iobroker/iobroker.node-red?logo=github&style=flat-square)
![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/iobroker/iobroker.node-red/test-and-release.yml?branch=master&logo=github&style=flat-square)

[![Translation status](https://weblate.iobroker.net/widgets/adapters/-/node-red/svg-badge.svg)](https://weblate.iobroker.net/engage/adapters/?utm_source=widget)

## Versions

![Beta](https://img.shields.io/npm/v/iobroker.node-red.svg?color=red&label=beta)
![Stable](http://iobroker.live/badges/node-red-stable.svg)
![Installed](http://iobroker.live/badges/node-red-installed.svg)

Instantiate the server with Node-RED

## Documentation

[🇺🇸 Documentation](./docs/en/README.md)

[🇩🇪 Dokumentation](./docs/de/README.md)

<!--
	Placeholder for the next version (at the beginning of the line):
    ### **WORK IN PROGRESS**
-->
## Changelog
### **WORK IN PROGRESS**

- (klein0r) Added persistence of context data (filesystem)

### 5.1.0 (2023-12-27)

- (klein0r) Allow custom themes
- (klein0r) Fixed scoped node-red packages

### 5.0.2 (2023-12-14)

- (TheRealArthurDent) Fixed a fatal error when getting a non-existent value

### 5.0.1 (2023-12-05)

- (klein0r) Fixed credentials decrypt
- (klein0r) Added connection state (process is running)

### 5.0.0 (2023-11-26)

**NodeJS 16.4.x is required**
**Please check instance configuration and re-enter your passwords (encryption has changed).**

- (klein0r) Updated Node-RED to 3.1.0. Please check your nodes for compatibility!
- (klein0r) Admin 5/6 JSON config for instance configuration
- (klein0r) Added sendTo node with callback
- (klein0r) Allow custom attribute name for "ioBroker in" node
- (klein0r) Added option to select editor (monaco, ace)
- (klein0r) Added table for custom env vars to instance configuration

### 4.0.3 (2023-03-24)

- (Apollon77) Optimized path handling

## License

Copyright 2014-2024 bluefox <dogafox@gmail.com>.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

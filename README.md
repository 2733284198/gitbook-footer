## page-footer

[![Pay](https://img.shields.io/badge/%24-free-%23a10000.svg)](#) [![GitHub issues](https://img.shields.io/github/issues/aleen42/gitbook-footer.svg)](https://github.com/aleen42/gitbook-footer/issues) [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/aleen42/gitbook-footer/master/LICENSE) [![npm version](https://badge.fury.io/js/gitbook-plugin-gitbook-footer.svg)](https://badge.fury.io/js/page-footer) [![Build Status](https://travis-ci.org/aleen42/gitbook-footer.svg?branch=master)](https://travis-ci.org/aleen42/gitbook-footer) 
[![devDependency Status](https://david-dm.org/aleen42/gitbook-footer.svg)](https://github.com/aleen42/gitbook-footer) [![Gitter](https://badges.gitter.im/aleen42/gitbook-footer.svg)](https://gitter.im/aleen42/gitbook-footer?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge) 

a gitbook-plugin for adding footer.

#### Installation

###### NPM Installation

```bash
npm install page-footer
cd ./node_modules/page-footer
npm i
```

###### Clone Installation

```bash
git clone https://github.com/aleen42/gitbook-footer.git
cd gitbook-footer
npm i
```

#### Usage

just find plugin on gitbook and install it on your gitbook project.

configuration option can be set as an obj like, and of course you can use a default value shown as followed:

```json
{
	"plugins": [
		"page-footer"
	],
	"pluginsConfig": {
		"page-footer": {
			"description": "modified at",
			"format": "YYYY-MM-DD HH:mm:ss",
			"copyright": "Copyright © aleen42",
			"timeColor": "#666",
			"copyrightColor": "#666"
		}
	}
}
```

#### Tests

```bash
npm test
```

#### Release History

* 1.0.0 Initial release
	* 1.0.1 fix bugs
	* 1.0.2 fix bugs
	* 1.0.3 fix bugs
	* 1.0.4 fix bugs
	* 1.0.5 fix bugs
	* 1.0.6 update readme
	* 1.0.7 update package.json
	* 1.0.8 update readme

#### :fuelpump: How to contribute

Have an idea? Found a bug? See [how to contribute](https://aleen42.gitbooks.io/personalwiki/content/contribution.html).

#### :scroll: License

[MIT](https://aleen42.gitbooks.io/personalwiki/content/MIT.html) © aleen42

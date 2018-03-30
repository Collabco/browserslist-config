# @collabco/browserslist-config

Collabco Browserslist shareable config for [Browserslist](https://www.npmjs.com/package/browserslist).

## Installation

Install the module

```shell
$ npm install @collabco/browserslist-config
```

## Usage

Add this to your `package.json` file:

```json
"browserslist": [
	"extends @wordpress/browserslist-config"
]
```

This package when imported returns an array of supported browsers, for more configuration examples including Autoprefixer, Babel, ESLint, PostCSS, and stylelint see the [Browserslist examples](https://github.com/ai/browserslist-example#browserslist-example) repo.

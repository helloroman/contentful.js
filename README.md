# contentful.js

[![npm](https://img.shields.io/npm/v/contentful.svg)](https://www.npmjs.com/package/contentful)
[![Build Status](https://travis-ci.org/contentful/contentful.js.svg?branch=master)](https://travis-ci.org/contentful/contentful.js)
[![Coverage Status](https://coveralls.io/repos/github/contentful/contentful.js/badge.svg?branch=master)](https://coveralls.io/github/contentful/contentful.js?branch=master)
[![Dependency Status](https://david-dm.org/contentful/contentful.js.svg)](https://david-dm.org/contentful/contentful.js)
[![devDependency Status](https://david-dm.org/contentful/contentful.js/dev-status.svg)](https://david-dm.org/contentful/contentful.js#info=devDependencies)

[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com/)

Javascript SDK for [Contentful's](https://www.contentful.com) Content Delivery API.

# About

[Contentful](https://www.contentful.com) is a content management platform for web applications, mobile apps and connected devices. It allows you to create, edit & manage content in the cloud and publish it anywhere via a powerful API. Contentful offers tools for managing editorial teams and enabling cooperation between organizations.

## Features

- Content retrieval through Contentful's [Content Delivery API](https://www.contentful.com/developers/docs/references/content-delivery-api/).
- [Synchronization](https://www.contentful.com/developers/docs/concepts/sync/)
- [Localization support](https://www.contentful.com/developers/docs/concepts/locales/)
- [Link resolution](https://www.contentful.com/developers/docs/concepts/links/)

## Supported environments

Browsers and Node.js:
- Chrome
- Firefox
- IE11 / Edge
- Safari
- node.js (0.10, iojs-3.x, 4.x, 5.x)

Other browsers should also work, but at the moment we're only running automated tests on the browsers and Node.js versions specified above.

# Getting started

In order to get started with the Contentful JS SDK you'll need not only to install it, but also to get credentials which will allow you to have access to your content in Contentful.

## Installation

In node, using [npm](http://npmjs.org):

``` sh
npm install contentful
```

Or, if you'd like to use a standalone built file you can use the following script tag or just download it from [npmcdn](https://npmcdn.com), under the `browser-dist` directory:

``` html
<script src="https://npmcdn.com/contentful@latest/browser-dist/contentful.min.js"></script>
```
**It is not recommended to use the above URL for production.**

Using `contentful@latest` will always get you the latest version, but you can also specify a specific version number:

``` html
<script src="https://npmcdn.com/contentful@3.0.0/browser-dist/contentful.min.js"></script>
```

Check the [releases](https://github.com/contentful/contentful.js/releases) page to know which versions are available.

## Authentication

To get content from Contentful, an app should authenticate with an with an OAuth bearer token.

You can create API keys using [Contentful's web interface](https://app.contentful.com). Go to the app, open the space that you want to access (top left corner lists all the spaces), and navigate to the APIs area. Open the API Keys section and create your first token. Done.

Don't forget to also get your Space ID.

For more information, check the Contentful's REST API reference on [Authentication](https://www.contentful.com/developers/docs/references/authentication/).

## Documentation/References

* [Contentful's JS SDK reference](https://contentful.github.io/contentful.js)
  * From version 3.0.0 onwards, you can access documentation for a specific version by visiting `https://contentful.github.io/contentful.js/contentful/<VERSION>`
  * For versions prior to 3.0.0, you can access documentation at [https://github.com/contentful/contentful.js/tree/legacy](https://github.com/contentful/contentful.js/tree/legacy)
* Check the [Contentful for JavaScript](https://www.contentful.com/developers/docs/javascript/) page for Tutorials, Demo Apps, and more information on other ways of using JavaScript with Contentful
* [Contentful's CDA REST API reference](https://www.contentful.com/developers/docs/references/content-delivery-api/) for additional details on the Delivery API

## Versioning

This project strictly follows [Semantic Versioning](http://semver.org/) by use of [semantic-release](https://github.com/semantic-release/semantic-release).

This means that new versions are released automatically as fixes, features or breaking changes are released.

You can check the changelog on the [releases](https://github.com/contentful/contentful.js/releases) page.

## Migration from contentful.js 2.x and older

contentful.js 3.x was a major rewrite, with some API changes. While the base functionality remains the same, some method names have changed, as well as some internal behaviors.

See the [migration guide](migration_from_2_x.md) for more information.

## Support

Please open an [issue](https://github.com/contentful/contentful.js/issues/new)

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md)

## License

MIT

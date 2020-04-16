# Tide Docs

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](CONTRIBUTING.md) [![Shipping faster with ZenHub.io](https://img.shields.io/badge/Shipping_faster_with-ZenHub.io-6567bd.svg?style=flat)](https://www.zenhub.com/)

Documentation for [wptide.org](http://wptide.org).

This repo uses a modified version of [Docpres](https://github.com/docpress/docpress) to allow integrating with WordPress. It's a very basic WordPress theme that resolves all routes into the main `index.php` file where they pull the static content generated by Docpress.

## Installation

To develop locally, run:
1. `git clone` to clone this repo to WordPress theme folder.
2. `npm install` to install the repo's dependencies.
3. `npm run link` to link the local docpress packages and install their dependencies.
4. `npm run dev` to build and watch assets or `npm run build` to just build the assets.
5. Activate the theme and visit the homepage.

## Development Notes

* `docpress` customized Docpress generator that we bundle with the theme
* `docs` is the root of the content source
* `src` contains all styles, scripts and layout
* `_docpress` is the build folder, never place anything here as it will get overwritten

### Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

### Contact Us

Have questions? Don't open an Issue, come join us in the [`#tide` channel](https://wordpress.slack.com/messages/C7TK8FBUJ/) in [WordPress Slack](https://make.wordpress.org/chat/). Even though Slack is a chat service, sometimes it takes several hours for community members to respond — please be patient.

### Maintainers

[Derek Herman (@valendesigns)](https://github.com/valendesigns), and
[Jeffrey Paul (@jeffpaul)](https://github.com/jeffpaul)

### Credits

Props: [Bartek Makoś (@MakiBM)](https://github.com/MakiBM),
[Cathi Bosco (@cathibosco)](https://github.com/cathibosco),
[Derek Herman (@valendesigns)](https://github.com/valendesigns),
[Janki Moradiya (@jankimoradiya)](https://github.com/jankimoradiya),
[Jeffrey Paul (@jeffpaul)](https://github.com/jeffpaul),
[Keanan Koppenhaver (@kkoppenhaver)](https://github.com/kkoppenhaver),
[Leo Postovoit (@postphotos)](https://github.com/postphotos),
[Mukesh Panchal (@mukeshpanchal27)](https://github.com/mukeshpanchal27),
[Otto Kekäläinen (@ottok)](https://github.com/ottok),
[Pierre Gordon (@pierlon)](https://github.com/pierlon),
[Prashant Baldha (@pmbaldha)](https://github.com/pmbaldha),
[Scott Reilly (@coffee2code)](https://github.com/coffee2code)

### License

Tide Docs utilizes an [MIT license](LICENSE).

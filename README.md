# Tide - Official Documentation

> A rising tide lifts all boats. -- United States President, John F. Kennedy (borrowed from the New England Council)

[![Build Status](https://travis-ci.org/wptide/wptide.svg?branch=develop)](https://travis-ci.org/wptide/wptide) [![Coverage Status](https://coveralls.io/repos/github/wptide/wptide/badge.svg?branch=develop)](https://coveralls.io/github/wptide/wptide?branch=develop) [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE.md) [![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](CONTRIBUTING.md)

Tide is an automated tool to provide insight into WordPress code and highlight areas to improve the quality of plugins and themes.

![](assets/images/screenshot.png)

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

Props: [Arslan Ahmed (@akkspros)](https://github.com/akkspros),
[Bartek Makoś (@MakiBM)](https://github.com/MakiBM),
[Cathi Bosco (@cathibosco)](https://github.com/cathibosco),
[Derek Herman (@valendesigns)](https://github.com/valendesigns),
[Janki Moradiya (@jankimoradiya)](https://github.com/jankimoradiya),
[Jeffrey Paul (@jeffpaul)](https://github.com/jeffpaul),
[Keanan Koppenhaver (@kkoppenhaver)](https://github.com/kkoppenhaver),
[Leo Postovoit (@postphotos)](https://github.com/postphotos),
[Morteza (@man4toman)](https://github.com/man4toman),
[Mukesh Panchal (@mukeshpanchal27)](https://github.com/mukeshpanchal27),
[Otto Kekäläinen (@ottok)](https://github.com/ottok),
[Pierre Gordon (@pierlon)](https://github.com/pierlon),
[Prashant Baldha (@pmbaldha)](https://github.com/pmbaldha),
[Scott Reilly (@coffee2code)](https://github.com/coffee2code)

### License

Tide Docs utilizes an [MIT license](LICENSE).

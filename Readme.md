<img src="https://raw.githubusercontent.com/hexojs/logo/master/hexo-logo-avatar.png" alt="Hexo logo" width="100" height="100" align="right" />

# Hexo

> A fast, simple & powerful blog framework, powered by [Node.js](https://nodejs.org).

[Website](https://hexo.io) |
[Documentation](https://hexo.io/docs/) |
[Installation Guide](https://hexo.io/docs/#Installation) |
[Contribution Guide](https://hexo.io/docs/contributing) |
[Code of Conduct](CODE_OF_CONDUCT.md) |
[API](https://hexo.io/api/) |
[Twitter](https://twitter.com/hexojs)

[![NPM version](https://badge.fury.io/js/hexo.svg)](https://www.npmjs.com/package/hexo)
![Required Node version](https://img.shields.io/node/v/hexo)
[![Build Status](https://github.com/hexojs/hexo/workflows/Tester/badge.svg)](https://github.com/hexojs/hexo/actions?query=workflow%3ATester)
[![dependencies Status](https://david-dm.org/hexojs/hexo/status.svg)](https://david-dm.org/hexojs/hexo)
[![devDependencies Status](https://david-dm.org/hexojs/hexo/dev-status.svg)](https://david-dm.org/hexojs/hexo?type=dev)
[![Coverage Status](https://coveralls.io/repos/hexojs/hexo/badge.svg?branch=master)](https://coveralls.io/r/hexojs/hexo?branch=master)
[![Gitter](https://badges.gitter.im/hexojs/hexo.svg)](https://gitter.im/hexojs/hexo)
[![Discord Chat](https://img.shields.io/badge/chat-on%20discord-7289da.svg)](https://discord.gg/teM2Anj)
[![Telegram Chat](https://img.shields.io/badge/chat-on%20telegram-32afed.svg)](https://t.me/hexojs)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fhexojs%2Fhexo.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fhexojs%2Fhexo?ref=badge_shield)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg)](CODE_OF_CONDUCT.md)

## Features

- Blazing fast generating
- Support for GitHub Flavored Markdown and most Octopress plugins
- One-command deploy to GitHub Pages, Heroku, etc.
- Powerful API for limitless extensibility
- Hundreds of [themes](https://hexo.io/themes/) & [plugins](https://hexo.io/plugins/)

## Quick Start

**Install Hexo**

``` bash
$ npm install hexo-cli -g
```

**Setup your blog**

``` bash
$ hexo init blog
$ cd blog
```

**Start the server**

``` bash
$ hexo server
```

**Create a new post**

``` bash
$ hexo new "Hello Hexo"
```

**Generate static files**

``` bash
$ hexo generate
```

## Theme I Used

# Hexo-Theme-Huxblog

> Ported Theme of [Hux Blog](https://github.com/Huxpro/huxpro.github.io), Thank [Huxpro](https://github.com/Huxpro) for designing such a flawless theme.

### [Demo &rarr;](http://kaijun.github.io/hexo-theme-huxblog)


![](http://huangxuan.me/img/blog-desktop.jpg)

## Usage

I didn't publish it as a single theme folder because a few of the pages are added and modified manually, so you should manually create some extra folders in `source` for the new pages and modify the `_config.yml` if you only have the single theme folder.

So i just pushed the whole hexo project for your convenience, all pre settings and boilerplates are included, have a look and go ahead customizing your own blog!

##### 1.Init

```
git clone https://github.com/Kaijun/hexo-theme-huxblog.git
cd hexo-theme-huxblog
npm install
```

##### 2.Modify
Modify `_config.yml` file with your own info.
Especially the section:

```
deploy:
  type: git
  repo: https://github.com/Kaijun/hexo-theme-huxblog
  branch: gh-pages
```
Replace with your own repo!

##### 3.Writting/Serve/Deploy

```
hexo new post IMAPOST
hexo serve // run hexo in local environment
hexo clean && hexo deploy // hexo will push the static files automatically into the specific branch(gh-pages) of your repo!
```

##### 4.Enjoy! 
Please [**Star**](https://github.com/kaijun/hexo-theme-huxblog/stargazers) this Project if you like it! [**Following**](https://github.com/Kaijun) would also be appreciated!




## More Information

- Read the [documentation](https://hexo.io/)
- Visit the [Awesome Hexo](https://github.com/hexojs/awesome-hexo) list
- Find solutions in [troubleshooting](https://hexo.io/docs/troubleshooting.html)
- Join discussion on [Google Group](https://groups.google.com/group/hexo), [Discord](https://discord.gg/teM2Anj), [Gitter](https://gitter.im/hexojs/hexo) or [Telegram](https://t.me/hexojs)
- See the [plugin list](https://hexo.io/plugins/) and the [theme list](https://hexo.io/themes/) on wiki
- Follow [@hexojs](https://twitter.com/hexojs) for latest news

## Contributing

We welcome you to join the development of Hexo. Please see [contributing document](https://hexo.io/docs/contributing). 🤗

Also, we welcome PR or issue to [official-plugins](https://github.com/hexojs).

## Contributors

[![](https://opencollective.com/Hexo/contributors.svg?width=890)](https://github.com/hexojs/hexo/graphs/contributors)

## Backers

[![Backers](https://opencollective.com/hexo/tiers/backers.svg?avatarHeight=36&width=600)](https://opencollective.com/hexo)

## License

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fhexojs%2Fhexo.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fhexojs%2Fhexo?ref=badge_large)

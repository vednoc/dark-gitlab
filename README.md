# dark-gitlab

A customizable Stylus theme for Gitlab and self-hosted GitLab instances made by [vednoc](https://gitlab.com/vednoc) and [@RaitaroH](https://gitlab.com/RaitaroH). 


# ToC
- [dark-gitlab](#dark-gitlab)
- [ToC](#toc)
- [Roadmap to v1.0.0](#roadmap-to-v100)
- [Features](#features)
- [Install](#install)
    - [Using a browser extension:](#using-a-browser-extension)
    - [Then install this style:](#then-install-this-style)
- [Screenshots](#screenshots)
- [Contributing](#contributing)


# Roadmap to v1.0.0

* [X] Make a better logo.
* [X] Add a banner.
* [ ] Add a license.
* [ ] Add a contribution guide.
* [ ] Add a changelog.
* [x] Write a concise readme.
* [ ] Add issue and merge request templates.
* [x] Convert to [Stylus-lang](https://stylus-lang.org):
  * [ ] Make a use of vars, nesting, etc.
  * [ ] Refactor existing CSS.
  * [ ] Full coverage.
* [ ] Convert to [BetterComments](https://github.com/aaron-bond/better-comments):
  * [ ] Full coverage.
* [ ] Cover most of the GitLab website.
* [x] Have a *decent* compatability with older versions and self-hosted instances.


# Features

* **Customizable colors**: Both light and dark color-schemes are fully supported; you can use built-in color picker to customize colors and/or use my [ThemeSwitcher](https://gitlab.com/vednoc/theme_switcher) to choose from already available presets. Tip: Use both, one for light and the other for dark color-scheme.
* **Customizable background**: Whether you like the default background or you want a custom image, color or nothing at all, you're able to do whatever you want from within the popup.
* **Custom regexp**: Support for public self-hosted GitLab instances. You can easily add your own by editing the `@-moz-document regexp(...)` locally (**Note**: that prevents the auto-update feature, unfortunately, but you can always force an update).
* **Custom code font**: Use your favorite font for code sections, i.e. FiraCode, Operator Mono, Iosevka, etc.
* **Old-design project header**: If you prefer to have the elements in the center, now you can have it back.
* **Complete theme**: for the entire UI; still very much WIP and it'll only get better with time.
* Anything else you'd like to have? Feel free to make a suggestion.


# Install

### Using a browser extension:
* Stylus - get the addon for [Firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us/), [Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne) and [Opera](https://addons.opera.com/en-gb/extensions/details/stylus/).

### Then install this style:  
[![Install directly with Stylus](https://img.shields.io/badge/Install%20directly%20with-Stylus-116b59.svg?longCache=true&style=for-the-badge)](https://gitlab.com/vednoc/dark-gitlab/raw/master/gitlab.user.styl)
  >Installs directly from this repository.  
  >This is only available using Stylus (see the [documentation](https://github.com/openstyles/stylus/wiki/Usercss)). :tada:


# Screenshots

Project page view with BreezeDark color-scheme from [ThemeSwitcher](h), max-width of 1300px and old project header design enabled.

![preview](images/preview.png)


# Contributing

Any contribution is greatly appreciated. If you'd like to tip me then you can buy me a coffee on [ko-fi](https://ko-fi.com/vednoc).

# dark-gitlab
Customizable Stylus theme for Gitlab and self-hosted GitLab instances.

<p align="center">
  <img alt="banner" src="./images/banner.png" width="600">
</p>

## Roadmap to v1.0.0
The userstyle looks and works great right now (and has been for quite some time!) but I just want to get everything refactored before publishing the v1.0.0 release.

- [x] Make a better logo.
- [x] Add a banner.
- [ ] Add a license.
- [ ] Add a contribution guide.
- [ ] Add a changelog.
- [x] Write a concise readme.
- [x] Add issue and merge request templates.
- [x] Convert to [Stylus-lang](https://stylus-lang.org):
  - [x] Make a use of vars, mixins, nesting, etc.
  - [x] Refactor existing CSS.
  - [ ] Full coverage.
- [x] Convert to [BetterComments](https://github.com/aaron-bond/better-comments):
  - [x] Use it with refactored CSS.
  - [ ] Full coverage.
- [x] Cover most of the GitLab website.
- [x] Have a _decent_ compatability with a few older versions for self-hosted instances. Might get dropped depending on the number of breaking changes.
- [ ] Add a version with USo preprocessor so xStyle and extensions that support UserCSS can install this theme.
  - [ ] Automate the process; not a high priority.

## Features
This is why you should consider using dark-gitlab!

- **Custom colors**: All color variables are easily customizable through Stylus popup menu. Both light and dark color-schemes are fully supported; use [ThemeSwitcher](https://gitlab.com/vednoc/theme_switcher) if you want to choose from presets or if you'd like to easily switch between light and dark color-schemes.
- **Custom background**: Gives you the full control of the background image.
- **Custom regex**: Support for public self-hosted GitLab instances. You can easily add your own by editing the `@-moz-document regexp(...)` locally ( :warning: **Note**: that unfortunately prevents the auto-update feature, but you can always force an update to get the newest version and re-do the regex).
- **Custom code font**: Use your favorite font for code sections, i.e. FiraCode, Operator Mono, Iosevka, etc.
- **Custom rounded corners value**: Set your prefered border-radius for main elements (excluding buttons).
- **Custom avatar radius**: Set your prefered border-radius for avatars.
- **Old-design project header**: If you prefer to have project header items in the center, now you can have it back.
- **Complete theme**: Mainly focusing on the core app but useful and often used sub-domains are also included.
- Anything else you'd like to see added? Feel free to make a [suggestion][new].

[new]: https://gitlab.com/vednoc/dark-gitlab/issues/new

## Installation
To go further you'll need a CSS injector extension for your browser. We highly recommend [Stylus](https://github.com/openstyles/stylus) since it's simply the best one out there.

### Get Stylus:
Get the extension for [Firefox][Firefox], [Chrome][Chrome] and [Opera][Opera].

[Firefox]: (https://addons.mozilla.org/en-US/firefox/addon/styl-us/)
[Chrome]: (https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)
[Opera]: (https://addons.opera.com/en-gb/extensions/details/stylus/)

### Install this theme:
[![Install directly with Stylus][badge]][style]

> Installs directly from this repository.  
> This is only available using Stylus (see the [documentation](https://github.com/openstyles/stylus/wiki/Usercss)). :tada:  
> :warning: :exclamation: **NOTE:** Also available at [userstyles.org](https://userstyles.org/styles/164877) _only_ so we can attract more users. Dark-gitlab there has just the core functionality and is manually updated once in a while. We highly encourage you to install dark-gitlab directly from this repository.

[badge]: https://img.shields.io/badge/Install%20directly%20with-Stylus-116b59.svg?longCache=true&style=for-the-badge
[style]: https://gitlab.com/vednoc/dark-gitlab/raw/master/gitlab.user.styl

### GitLab settings:
The theme works best with the default settings and it's not extensively tested with GitLab's default presets. Go to `settings -> preferences` and select indigo for the navigation theme and white for the syntax highlighting.

### Further customization:
Open the Stylus extension popup while you're on any GitLab page, click on the cogwheel icon and that'll open up a menu from which you can set your own preferences.

:warning: **NOTE:** To use "maximum width for fluid layout" go to `settings -> preferences` and change the layout from fixed to fluid.

## Screenshots
*Keep in mind these screenshots are taken a while ago.*

Project page view with BreezeDark color-scheme from [ThemeSwitcher](https://gitlab.com/vednoc/theme_switcher), max-width of 1300px and old project header design enabled.

![preview](./images/preview.png)

Default everything except max-width of 1300px:

![default](./images/Default.png)

Solarized light/dark color-scheme:

![Solarized](./images/Solarized.png)

Gruvbox light/dark color-scheme:

![Gruvbox](./images/Gruvbox.png)

## Contributing
Any contribution is greatly appreciated. If you really like the project and would like to tip me then you can buy me a coffee over at [ko-fi](https://ko-fi.com/vednoc).

## Contributors
- [vednoc](https://gitlab.com/vednoc) - creator, maintainer
- [RaitaroH](https://gitlab.com/RaitaroH) - maintainer
- All lovely people that reported issues and made merge requests.

[![Install directly with Stylus][badge]][style]

Dark-GitLab is opinionated, dark and light, very customizable [Stylus][stylus] userstyle for Gitlab and self-hosted GitLab instances.

For roadmap see %1.

## Features
This is why you should consider using Dark-GitLab!

- **Custom colors**: All color variables are easily customizable through Stylus popup menu. Both light and dark color-schemes are fully supported.
- **Custom background**: Gives you the full control of the background image.
- **Custom regex**: OOTB support for known public self-hosted GitLab instances.
  - Add your own by editing the `@-moz-document regexp(...)` locally.
  - :warning: **Note**: Editing locally prevents auto-updating, but you can always force an update to get the newest version and re-do the regex.
- **Custom image opacity**: Lower the opacity of images until you hover over them.
- **Custom UI font**: Use your favorite font for the entire UI except code/emoji sections.
- **Custom code font**: Use your favorite font for code sections, i.e. FiraCode, Operator Mono, Iosevka, etc.
- **Custom emoji font**: Use your favorite font for emojis, i.e. emojione, twemoji, etc.
- **Custom rounded corners value**: Set your prefered border-radius for main elements (excluding buttons).
- **Custom transitions**: Set custom transitions.
- **Custom avatar radius**: Set your prefered border-radius for avatars.
- **Old-design project header**: If you prefer to have project header items in the center, now you can have it back.
- **Complete theme**: Mainly focusing on the core app but useful and often used sub-domains are also included.
- Anything else you'd like to see added? Feel free to make a [suggestion][new].

## Installation
- Get Stylus extension for [Firefox][amo], [Chrome][cws] or [Opera][aoe].
- Install the userstyle by clicking on the badge or [this link][style].
  - Installs directly from this repository.
  - Only available using Stylus (see the [docs][usercss]). :tada:
  - :exclamation: **NOTE:** Also available at [userstyles.org][style-uso] _only_
    so more users can discover the userstyle.
    - It only has core functionality, is (likely) outdated, has no support,
    and needs to be _manually_ compiled for every single update. Just don't use
    it unless you really have no choice.
- Change GitLab preferences because Dark-GitLab is meant to be used both when
  the user is signed in and signed out. Therefore, for best experience set the
  following in `settings -> preferences`:
  - Set syntax highlighting theme set to `white`.
  - Set navigation theme to `indigo`.
  - Set layout to `fluid` if wanna use "custom width for fluid layout" feature.
- Further customization:
  - Open the Stylus extension popup while you're on any GitLab page or from the
    Manage page in Stylus, click on the cogwheel icon and that'll open up a menu
    from which you can set your own preferences.
  - Additionally, install [ThemeSwitcher][switcher] if you'd like to quickly
    switch between various pre-defined color-schemes.

## Screenshots
Preview image showcases v0.46.0 with default colors, custom width of 1440px, Inter as the UI font, and Iosevka as the mono font on 1920x1080 resolution.

![preview](./images/preview.png)

## Contributing
Any contribution is greatly appreciated. If you really like the project and would like to tip me then you can buy me a coffee over at [ko-fi](https://ko-fi.com/vednoc).

## Contributors
- [vednoc](https://gitlab.com/vednoc) - creator, maintainer
- [RaitaroH](https://gitlab.com/RaitaroH) - code, testing, ideas
- All lovely people that reported issues and made merge requests.

<!-- References. -->
[amo]: https://addons.mozilla.org/en-US/firefox/addon/styl-us/
[cws]: https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne
[aoe]: https://addons.opera.com/en-gb/extensions/details/stylus/
[new]: https://gitlab.com/vednoc/dark-gitlab/issues/new
[badge]: https://img.shields.io/badge/Install%20directly%20with-Stylus-116b59.svg?longCache=true&style=for-the-badge
[style]: https://gitlab.com/vednoc/dark-gitlab/raw/master/gitlab.user.styl
[stylus]: https://github.com/openstyles/stylus
[switcher]: https://gitlab.com/vednoc/theme_switcher
[style-uso]: https://userstyles.org/styles/164877

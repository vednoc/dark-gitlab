![alt tag](./images/banner.png)

## Roadmap to v1.0.0

* [X] Make a better logo.
* [X] Add a banner.
* [ ] Write a concise readme.
* [ ] Add issue and merge request templates.
* [ ] Convert to [Stylus-lang](https://stylus-lang.org):
  * [ ] Make a use of vars, nesting, etc.
  * [ ] Refactor existing CSS.
  * [ ] Full coverage.
* [ ] Convert to [BetterComments](https://github.com/aaron-bond/better-comments):
  * [ ] Full coverage.
* [ ] Cover most of the GitLab website.
* [ ] Have a *decent* compatability with older versions and self-hosted instances.
* 
A customizable Stylus theme for Gitlab made by [vednoc](https://gitlab.com/vednoc) and [@RaitaroH](https://gitlab.com/RaitaroH). 


# Description

* Whole UI is styled to match the overall theme
* Customizable colors, wide variety of light and dark color-schemes supported, using the [theme_switcher](https://gitlab.com/vednoc/theme_switcher)
* Custom background images can be set in the settings
* Custom red, green, cyan etc colors that are perfectly chosen for each color scheme (Solarized, Gruvbox, BreezeDark)
* Custom regexp


# Install

### Using a browser extension:
* Stylus - get the addon for [Firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us/), [Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne) and [Opera](https://addons.opera.com/en-gb/extensions/details/stylus/).

### Then install this style:  
[![Install directly with Stylus](https://img.shields.io/badge/Install%20directly%20with-Stylus-116b59.svg?longCache=true&style=for-the-badge)](https://gitlab.com/vednoc/dark-gitlab/raw/master/gitlab.user.styl)
  >Installs directly from this repository.  
  >This is only available using Stylus (see the [documentation](https://github.com/openstyles/stylus/wiki/Usercss)). :tada:


# I Found a Bug

At the first instance of finding a bug, have a look if there is already an open issue, if so add the required information as described in the [issue template](.github/ISSUE_TEMPLATE.md).


# Contributions

You will need to ideally:

* [Fork](https://gitlab.com/vednoc/dark-gitlab/forks/new) the project.

* Limit to the [K&R (KNF variation style)](https://en.wikipedia.org/wiki/Indentation_style#Variant:_BSD_KNF), and **1 TAB INDENTATION** (not more, and not less than 1 tab).

  * K&R - KNF Variation Example:
	```css
	element[attr='value'] {
	-property: value;
	}
	```

  * **Not Allman**
	```css
	element[property='value']
	{
	-property: value;
	}
	```

  * Strict space between the `selector` and the `{`:
	```css
	/* good */
	element[attr='value'] { }

	/* bad */
	element[attr='value']{ }
	```

  * 1 tab indentation
	```css
	/* good */
	-property: value;

	/* bad */
	····property: value;
	----property: value;
	·property: value;
	```

Try to wrap lines at around 80 characters.


# Screenshots

![preview](images/preview.png)


# Donations

Any sort of contribution is more than welcome. If you'd like to tip me then you can buy me a [ko-fi](https://ko-fi.com/vednoc).


# License

[![MIT](https://img.shields.io/badge/License-MIT-blue.svg?longCache=true&style=for-the-badge)](LICENSE)

[![Author](https://img.shields.io/badge/author-Daniel%20M.%20Hendricks-lightgrey.svg?colorB=9900cc )](https://www.danhendricks.com?utm_source=github.com&utm_medium=campaign&utm_content=button&utm_campaign=dmhendricks%2Ffile-icon-vectors)
[![Icon Count](https://img.shields.io/badge/icon%20count-1170-red.svg)](https://fileicons.org/?utm_source=github.com&utm_medium=referral&utm_content=button&utm_campaign=dmhendricks%2Ffile-icon-vectors)
[![Release](https://img.shields.io/github/release/dmhendricks/file-icon-vectors.svg)](https://github.com/dmhendricks/file-icon-vectors/releases)
[![License](https://img.shields.io/badge/license-MIT-yellow.svg)](https://raw.githubusercontent.com/dmhendricks/file-icon-vectors/master/LICENSE)
[![GitHub Downloads](https://img.shields.io/packagist/dt/dmhendricks/file-icon-vectors.svg?label=GitHub%20downloads)](https://github.com/dmhendricks/file-icon-vectors/releases)
[![NPM](https://img.shields.io/npm/v/file-icon-vectors.svg)](https://www.npmjs.com/package/file-icon-vectors?utm_source=github.com&utm_medium=referral&utm_content=button&utm_campaign=dmhendricks%2Ffile-icon-vectors)
[![NPM Downloads](https://img.shields.io/npm/dt/file-icon-vectors.svg?label=npm%20downloads)](https://www.npmjs.com/package/file-icon-vectors?utm_source=github.com&utm_medium=referral&utm_content=button&utm_campaign=dmhendricks%2Ffile-icon-vectors)
[![Twitter](https://img.shields.io/twitter/url/https/github.com/dmhendricks/file-icon-vectors.svg?style=social)](https://twitter.com/danielhendricks)

# File Icon Images

A collection of file type/extension SVG icons, available free for use in your applications.

* Please post [feedback or issues](https://github.com/dmhendricks/file-icon-vectors/issues).
* I pay to license several of the icons used in these sets. [Donations](https://paypal.me/danielhendricks) are appreciated.
* :bulb: If you have an idea, such as new icon requests, additional collections/designs, and/or are willing to contribute a library/design, please [let me know](https://github.com/dmhendricks/file-icon-vectors/issues)! My time is limited, but I will get to it eventually.
* :star: If you use these icons to create something cool, [tell me](https://twitter.com/danielhendricks) about it!

### :pushpin: Demo: [View Icons](https://fileicons.org/)

## Icon Sets

Currently, there are three icon sets in the `dist/icons` directory:

* **Classic** - An expansion of the Redboot [free-file-icons](https://github.com/redbooth/free-file-icons) designs.
* **Vivid** - Inspired by [Erlen Masson](https://www.sketchappsources.com/svg-resource/1856-vector-file-type-icons-sketch-freebie-resource.html?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors)
* **Square Outline** (in progress) - Modified from and inspired by [Cotne Nazarashvili](https://github.com/thecotne/square-file-icons)

**Next release:**

- Over 500 new icons
- A new set for dark backgrounds ([preview](https://fileicons.org/?branch=develop&view=high-contrast))
- CDNJS hosting

Once that is released, I'd like to focus on a webfont, ideally where you can create your own file icons with stacking, just like Font Awesome.

## Installation

### NPM

```bash
npm install file-icon-vectors
```

### Bower

```bash
bower install file-icon-vectors
```

:rotating_light: **NB!** Because I didn't use semver, the current release is not available from Bower. It will be corrected with the next release.

### Composer

```bash
composer require dmhendricks/file-icon-vectors
```

(I know, it doesn't below on Packagist, but 15% of my downloads are coming from there, so some people must prefer it.)

## Quick Start

To display a file icon, simply link to one or all of the icon set CSS files in the `css` directory:

```html
<link rel="stylesheet" href="dist/file-icon-classic.min.css" />
<link rel="stylesheet" href="dist/file-icon-square-o.min.css" />
<link rel="stylesheet" href="dist/file-icon-vivid.min.css" />

<!-- Alternatively, you can load all sets: -->
<link rel="stylesheet" href="dist/file-icon-vectors.min.css" />
```

### CDN: jsDelivr

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/file-icon-vectors@1.0.0/dist/file-icon-classic.min.css" />
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/file-icon-vectors@1.0.0/dist/file-icon-square-o.min.css" />
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/file-icon-vectors@1.0.0/dist/file-icon-vivid.min.css" />

<!-- Alternatively, you can load all sets: -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/file-icon-vectors@1.0.0/dist/file-icon-vectors.min.css" />
```

#### Combining Files

jsDelivr allows you to [combine](https://www.jsdelivr.com/features#combine) multiple files. Below is an example of linking both the Vivid and Square Outline sets with one URI:

```html
<link rel="stylesheet" href="//cdn.jsdelivr.net/combine/npm/file-icon-vectors@1.0.0/dist/file-icon-vivid.min.css,npm/file-icon-vectors@1.0.0/dist/file-icon-square-o.min.css" />
```

This will become more beneficial with future releases that contain supplementary packs, web fonts, etc.

### CDN: unpkg

```html
<link rel="stylesheet" href="https://unpkg.com/file-icon-vectors@1.0.0/dist/file-icon-classic.min.css" />
<link rel="stylesheet" href="https://unpkg.com/file-icon-vectors@1.0.0/dist/file-icon-square-o.min.css" />
<link rel="stylesheet" href="https://unpkg.com/file-icon-vectors@1.0.0/dist/file-icon-vivid.min.css" />

<!-- Alternatively, you can load all sets: -->
<link rel="stylesheet" href="https://unpkg.com/file-icon-vectors@1.0.0/dist/file-icon-vectors.min.css" />
```

### CDN: GitHack

Supports branches as endpoints (such as `master`).

```html
<link rel="stylesheet" href="https://rawcdn.githack.com/dmhendricks/file-icon-vectors/master/dist/file-icon-classic.min.css" />
<link rel="stylesheet" href="https://rawcdn.githack.com/dmhendricks/file-icon-vectors/master/dist/file-icon-square-o.min.css" />
<link rel="stylesheet" href="https://rawcdn.githack.com/dmhendricks/file-icon-vectors/master/dist/file-icon-vivid.min.css" />

<!-- Alternatively, you can load all sets: -->
<link rel="stylesheet" href="https://rawcdn.githack.com/dmhendricks/file-icon-vectors/master/dist/file-icon-vectors.min.css" />
```

### WordPress

If you're using WordPress, you can load the icons by adding the following line to your theme's `functions.php` file:

```php
wp_enqueue_style( 'file-icon-vectors', 'https://cdn.jsdelivr.net/npm/file-icon-vectors@1.0.0/file-icon-vectors.min.css', null, null );
```

## Usage

Each set has its own CSS prefix:

- `cla` - Classic
- `viv` - Vivid
- `sqo` - Square Outline

The format for CSS classes is `fiv-[prefix]-[extension]`:

```html
<span class="fiv-cla fiv-icon-ppt"></span>
<span class="fiv-cla fiv-icon-xls"></span>
<span class="fiv-viv fiv-icon-pdf"></span>
<span class="fiv-viv fiv-icon-wav"></span>
<span class="fiv-sqo fiv-icon-doc"></span>
```

If you want to override the size of the icons, you can do so with CSS:

```html
<style>
   .fiv-cla, .fiv-viv, .fiv-sqo { font-size: 3em; }
</style>
```

Alternatively, you may also use `.fiv-size-md`, `.fiv-size-lg` and `.fiv-size-xl` to modify the icon sizes:

```html
<span class="fiv-viv fiv-icon-pdf fiv-size-lg"></span>
```

## Catalog JSON

Each icon set has a `catalog.json` file that includes all icons included in the library. You can optionally use this to check for files that exist, and where missing, set an alternate icon.

For example, [fileicons.org](https://fileicons.org/) reads this file to dynamically create the icon lists for both release and development versions.

Generic icons include `blank.svg`, `folder.svg`, `image.svg`.

:rotating_light: **BREAKING CHANGE:** I will be removing the generic `folder.svg` from each collection in favor of the upcoming ["Extra"](https://fileicons.org/?branch=develop&view=extra) set. Follow this repo if you'd like to be notified when that happens.

## Special Thanks

- [jsDelivr](https://www.jsdelivr.com/?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors), [GitHack](https://raw.githack.com/?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors), and [unpkg](https://unpkg.com/?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors)
- [The File Extensions Database](https://fileinfo.com/?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors) and [Share Icon](https://www.shareicon.net/?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors)
- [SVG Optimizer](https://github.com/svg/svgo/?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors), [imagemin](https://github.com/imagemin/imagemin/?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors) and [SVGOMG](https://jakearchibald.github.io/svgomg/?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors)
- [Gulp](https://gulpjs.com/?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors) and [Sass](https://sass-lang.com/?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors)
- [Markdown Editor](https://jbt.github.io/markdown-editor/?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors) by James Taylor

Even though I'm paying for them, thanks also to [Adobe](https://www.adobe.com/?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors), [The Noun Project](https://thenounproject.com/?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors), [FlatIcon](https://www.flaticon.com/?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors), [Icons8](https://icons8.com/?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors) and [iconscout](https://iconscout.com/?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors) for providing great tools and services. :+1: :smile:

[![Analytics](https://ga-beacon.appspot.com/UA-126205765-1/dmhendricks/file-icon-vectors?flat)](https://ga-beacon.appspot.com/?utm_source=github.com&utm_medium=campaign&utm_content=button&utm_campaign=dmhendricks%2Ffile-icon-vectors)

## Legal Stuff

All icons used in the creation of this library were licensed MIT, Creative Commons ([attribution](#attribution)) or purchased royalty-free. Any exceptions noted below. All logos are copyright their respective owners.

If you feel that you have a copyright issue, please feel free to [report it](https://github.com/dmhendricks/file-icon-vectors/issues).

### Attribution

* [Android](https://www.flaticon.com/free-icon/android-logo_61120?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors) icon provided by [Google](https://www.flaticon.com/authors/google?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors) via [flaticon.com](https://www.flaticon.com/?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors)
* [Apple](https://github.com/simple-icons/simple-icons/blob/develop/icons/apple.svg?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors), [Debian](https://github.com/simple-icons/simple-icons/blob/develop/icons/debian.svg?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors), [Internet Explorer](https://github.com/simple-icons/simple-icons/blob/develop/icons/internetexplorer.svg?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors) icons provided by [Simple Icons](https://simpleicons.org/?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors)
* [Adobe Flash](https://github.com/vscode-icons/vscode-icons/blob/master/icons/file_type_flash.svg?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors) icon provided by [vscode-icons](https://github.com/vscode-icons/vscode-icons/?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors)
* [QuickTime](https://www.flaticon.com/free-icon/quicktime_732104?utm_source=github.com&utm_medium=campaign&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors), [Chrome](https://www.flaticon.com/free-icon/chrome_732205?utm_source=github.com&utm_medium=campaign&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors) and [Firefox](https://www.flaticon.com/free-icon/firefox_732023?utm_source=github.com&utm_medium=campaign&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors) icons provided by [Pixel Perfect](https://www.flaticon.com/authors/pixel-perfect?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors) via [flaticon.com](https://www.flaticon.com/?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors)
* [.NET](https://github.com/konpa/devicon/blob/master/icons/dot-net/dot-net-original.svg?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors), [CoffeeScript](https://github.com/konpa/devicon/blob/master/icons/coffeescript/coffeescript-original.svg?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors), [Git](https://github.com/konpa/devicon/blob/master/icons/git/git-plain.svg?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors), [RedHat](https://github.com/konpa/devicon/blob/master/icons/redhat/redhat-plain.svg?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors) icons provided by [Devicon](http://konpa.github.io/devicon/)
* [Nintendo Switch](https://www.flaticon.com/free-icon/nintendo-switch_871377?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors) icon provided by  [flaticon.com](https://www.flaticon.com/?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors)
* [BitTorrent](http://www.icons101.com/icon/id_73504/setid_2388/Minimalist_Black_Icons__WIP_by_noshery/bittorrent?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors) icon provided by [noshery](http://www.icons101.com/artist/id_2388/noshery) from [icons101.com](http://www.icons101.com/?utm_source=github.com&utm_medium=campaign&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors)
* [GIMP](https://icons8.com/icon/39867/gimp), [PowerShell](https://icons8.com/icon/59499/powershell) icons provided by [Icons8 LLC](https://icons8.com/?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors)
* [Sass](https://www.onlinewebfonts.com/icon/411905), [Globe](https://www.onlinewebfonts.com/icon/336552) icons provided by [oNline Web Fonts](http://www.onlinewebfonts.com?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors)
* Classic set [Folder Icon](https://www.iconfinder.com/icons/173016/close_folder_icon) made by [Snip Master](https://www.iconfinder.com/snipicons) from [Iconfinder](https://www.iconfinder.com?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors)
* [GNU](https://commons.wikimedia.org/wiki/File:Gnu-head-30-years-anniversary.svg) icon from [Be..anyone](https://commons.wikimedia.org/wiki/User:Be..anyone) at [Wikimedia Commons](https://commons.wikimedia.org/?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors)
* [Classic Windows](https://commons.wikimedia.org/wiki/File:Microsoft_Logo_Wingdings_Font.svg) icon from [Wdwdbot](https://commons.wikimedia.org/wiki/User:Wdwdbot) at [Wikimedia Commons](https://commons.wikimedia.org/?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors)
* [Maven](https://www.onlinewebfonts.com/icon/161017?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors) icon provided by [OnlineWebFonts](https://www.onlinewebfonts.com/?utm_source=github.com&utm_medium=referral&utm_content=link&utm_campaign=dmhendricks%2Ffile-icon-vectors)

## Screenshot

![Icon Samples](https://dmhendricks.github.io/demo/file-icon-vectors/assets/images/screenshot.png "Sample Icons")

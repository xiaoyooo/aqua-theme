# Aqua Theme

This theme is an evolving attempt to make Sublime Text 2 visually feel more native on OS X. The theme began as a fork of the [Soda Theme](https://github.com/buymeasoda/soda-theme).

## Design

#### ProKit
![ProKit](http://i.imgur.com/Dm4Pv.png)

#### AppKit
![AppKit](http://i.imgur.com/tY9Si.png)

## Installation

The best way to install the Aqua theme is through [Package Control](http://wbond.net/sublime_packages/package_control) (coming soon, for now you must clone the GitHub repo as described below).

If you do not wish to use Package Control, clone this repository directly into the `Packages` directory in the Sublime Text 2 application settings area (`~/Library/Application Support/Sublime Text 2/Packages` on OS X). The git clone command would be as follows:

    git clone https://github.com/cafarm/aqua-theme.git "Theme - Aqua"

## Activating the theme

To configure Sublime Text 2 to use the theme:

* For Sublime Text 2 (Build 2174) and later - Open your User Settings Preferences file `Sublime Text 2 -> Preferences -> Settings - User`. For earlier builds - Open your User Global Settings Preferences file `Sublime Text 2 -> Preferences -> Global Settings - User`
* Add (or update) your theme entry to be `"theme": "AppKit.sublime-theme"` or `"theme": "ProKit.sublime-theme"`

### Example User Settings

    {
        "theme": "AppKit.sublime-theme"
    }

You will have to restart Sublime for the theme to take full effect.

## Bonus Options

### Syntax Highlighting Color Schemes

The Aqua theme includes four of the best color schemes available (two light, two dark). Each color scheme has been modified from its original version to work well with Aqua. Color schemes are activated via `Preferences -> Color Scheme -> Theme - Aqua` in Sublime Text 2.

#### Espresso Aqua
![espresso aqua](http://i.imgur.com/UPmHq.png)

#### Tomorrow Aqua
![tomorrow aqua](http://i.imgur.com/HRrCl.png)

#### Monokai Aqua
![monokai aqua](http://i.imgur.com/o8wWY.png)

#### Tomorrow Night Aqua
![tomorrow night aqua](http://i.imgur.com/QEdne.png)

### Fold [...] Image

Interested in an improved fold [...] image? In the current version of Sublime this image is hard-coded to the `Theme - Default` folder. Once you've installed Aqua, overwrite `Packages/Theme - Default/fold.png` with `Packages/Theme - Aqua/AppKit/fold.png`.

![fold](http://i.imgur.com/t1YGB.png)

## Legals

This theme contains some icons from the excellent [Pictos](http://pictos.drewwilson.com/) series by Drew Wilson. Any use of these icons, other than for the purpose of the theme itself, would need to comply with Drew's [icon licensing agreement](http://stockart.drewwilson.com/license/).
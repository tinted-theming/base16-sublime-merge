# Base16 for Sublime Merge

This template maps the [base16-schemes] to [Sublime Merge] theme files.
See the [Tinted Theming] repo for more information or have a look at the
[base16-gallery] for more details about the colorschemes.

## Installation

Clone this repo into your Sublime Merge Package directory. You can
find this directory by opening `Sublime Merge -> Preferences -> Browse
Packages...`.

Once you have that path clone this repo to:

```shell
git clone https://github.com/tinted-theming/base16-sublime-merge.git /path/to/sublime-merge/Packages/base16-sublime-merge
```

For use with [base16-shell] hooks, make sure the directory name the
repository is cloned to is specifically `base16-sublime-merge`.

## Usage

Open your Sublime Merge Settings file. `Sublime Merge -> Preferences ->
Edit Settings...` and make sure the `theme` and `color_scheme` values
are set matching the base16 theme you want to set:

```json
{
    "theme": "base16-<BAS16_SCHEME_NAME>.sublime-theme",
    "color_scheme": "base16-<BAS16_SCHEME_NAME>.sublime-color-scheme"
}
```

Head over to the [base16-gallery] to find a new scheme name to use. Here
is an example with `ayu-dark` scheme set:

```json
{
    "theme": "base16-ayu-dark.sublime-theme",
    "color_scheme": "base16-ayu-dark.sublime-color-scheme"
}
```

Disclaimer: Some of the colorschemes have issues since the template is
used for over 200 schemes and getting them all to be perfect can be a
challenge. I'll have a closer look at the issues if there are requests
for it.

## Thanks

Thanks to [Meetio Theme] for creating such high quality SublimeMerge
themes. I used their source code in generating the template used here.

[Meetio Theme]: https://github.com/meetio-theme/merge-meetio-theme
[Tinted Theming]: https://github.com/tinted-theming/home
[base16-schemes]: https://github.com/tinted-theming/base16-schemes
[Sublime Merge]: https://www.sublimemerge.com/
[base16-gallery]: https://tinted-theming.github.io/base16-gallery/
[base16-shell]: https://github.com/tinted-theming/base16-shell

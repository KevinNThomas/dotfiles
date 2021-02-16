# dotfiles

![Desktop Screenshot](desktop.png)

## alacritty

I use the Dracula alacritty theme from here: https://draculatheme.com/alacritty

## bspwm

I use the rounded corner patch (includwed in the folder).

## firefox

Theme is based on
[minimal-function-fox](https://github.com/mut-ex/minimal-functional-fox).
See the README of that repo for how to get it setup. I only ended up using the
userChrome.css and userContent.css files for my setup.

Install the [nightTab](https://addons.mozilla.org/en-US/firefox/addon/nighttab/)
extension to get the new tab page shown in my screenshot.

## mopidy

I have mopidy and mpd installed, and use the extensions mopidy-mpd, mopidy-subidy, and mopidy-scrobbler

## ncmpcpp

I have configured the layout to my liking, and also use vim keybindings. The `bindings` file goes in my `~/.ncmpcpp` directory.

## pcmanfm

I have changed the settings to my liking and added the "hide menubar" patch.

## picom

I believe I use pretty standard settings for this.

## polybar

My polybar files are based on the "polybar-4" theme from this repo:
https://github.com/adi1090x/polybar-themes. If you wish to recreate my polybar
look, you can either use this theme or my files as a starting point. My files
will have most of the things taken out that aren't used directly in my polybar,
so keep that in mind if you want to add things that aren't in my bar.

To get started, copy the contents of the `polybar` directory into:
`~/.config/polybar`

### fonts

I use the Ubuntu Condensed for the main font, and icomoon-feather for the icon
font. These can be found in the `fonts` directory, and should be added to your
system fonts to be useable. I copy mine into `/usr/share/fonts`, then run
`fc-cache -f -v`.

### colors

Colors can be configured in `colors.ini`, and can be accessed using the form:
`${color.background}`.

### config

My config has two bars, my main bar and my sytem tray bar.

### modules

Contains configs for modules built into polybar.

### user_modules

Contains modules created by me. This is also where I recommend adding your own
custom modules.

### launching

Make sure `launch.sh` is executable by running: `chmod +x launch.sh`.
Add `launch.sh` as a startup script so polybar launches every time you log in.

## rofi

I use the Dracula rofi theme from here: https://draculatheme.com/rofi. I also use the rofi-power-menu script for a power menu launched from polybar.

## sxhkd

For bspwm and rofi keybindings.

## vscode

### extensions

Install the Dracula extension. I also use the

### settings.json

Contains the relevant parts of my `settings.json` file.



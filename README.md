# Guide for install basic enviroment
Download files from github.com/rlukin
## TODO:
 - [ ] Add scripts from /usr/share/i3block* in repo
 - [ ] Change wallpaper path and name

## Install this:
 - i3
 - compton
 - i3blocks
 - arc theme
 - feh
 - lxappearance
 - guake

apply any arc in lxappearance

## Change fonts to "Display System Sanfrancisco"
 - vi .gtkrc-2.0
 - vi .config/gtk-3.0/settings.ini 

## For firefox use stylish. Create a theme whith that supa dark theme fix:
```
input:not(.urlbar-input):not(.textbox-input):not(.form-control):not([type='checkbox']) {
    -moz-appearance: none !important;
    background-color: white;
    color: black;
}

#downloads-indicator-counter {
    color: white;
}

textarea {
    -moz-appearance: none !important;
    background-color: white;
    color: black;
}

select {
    -moz-appearance: none !important;
    background-color: white;
    color: black;
}
```

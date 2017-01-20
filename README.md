# Guide for install basic enviroment
Download files from github.com/rlukin/dotfiles
## TODO:
 - [ ] Add scripts from /usr/share/i3block* in repo
 - [ ] Change wallpaper path and name
 - [ ] Merge with my config from work

## Install this:
 - i3
 - compton
 - i3blocks
 - arc theme
 - feh
 - lxappearance
 - guake
 - Firefox
  * vimfx
  * stylish
  * hide caption titlebar plus 
  * firebug 
  * Arc Darker Theme, Arc Dark Theme

apply any arc in lxappearance

## Change fonts to "Display System Sanfrancisco"
for fix lxapperance bug, do it manualy
 - vi .gtkrc-2.0
 - vi .config/gtk-3.0/settings.ini 

## For firefox use stylish. Create a theme whith that supa dark theme fix:
by default firefox dont change background for input fields, so you have grey text on white background
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

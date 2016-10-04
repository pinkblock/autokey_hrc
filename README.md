Home row computing for Linux

## Overview

The basic idea here is to use the hyper and meta keys 
to move all the most use full keys to the home row. 
This is achieved modifying the system xkb
and also by using the program autokeys.

## Installations

Install auto keys...

    https://github.com/autokey/autokey/wiki/Installing-AutoKey

pull this repo
make a symbolic link from autokey in this repo to ~/.config/autokey
copy pc to /usr/share/X11/xkb/symbols

Clear the cash

    sudo rm -rf /var/lib/xkb/*

restart x

    sudo restart mdm

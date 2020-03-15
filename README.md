# mpdmenu

## Description
Simple dmenu frontend for MPD.

## Dependencies
Package | Description
:--- | :---
mpd | music player daemon
mpc | CLI client for mpd
[dmenu fork](https://github.com/samedamci/dmenu) | simple app/script menu

## Arguments

Pass mpdmenu arguments first, followed by any dmenu arguments. They are separated by `::`. For example:

    mpdmenu -p :: -sb '#000000'

`-l` is library mode (default), which descends artists and albums. `-p` is
playlist mode, which selects a track from the current playlist.

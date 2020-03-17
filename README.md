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
```
mpdmenu -p :: -sb '#000000'
```

### Modes
Argument | Function
:--- | :---
`-l` | library mode, artists -> albums (default)
`-p` | playlist mode
`-s` | song mode
`-a` | ask which mode use

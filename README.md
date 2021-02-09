# mpdmenu

Simple [dmenu](https://tools.suckless.org/dmenu/) frontend for [MPD](https://www.musicpd.org/).

### Usage

    $ mpdmenu [-p | -l] [:: DMENU_ARGS]
         -p playlist mode, selects a track from the current playlist
         -l library mode (default), descends artists and albums

Additional arguments for `dmenu` can be passed after `::`.
For example:

    mpdmenu -p :: -sb '#000000'

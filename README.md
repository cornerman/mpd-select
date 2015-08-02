# mpd-select

Control mpd with dmenu.

## Features

- Add playlists
- Add via artist, album or title
- Goto song in playlist
- Remove songs from playlist
- Shuffle playlist
- Clear playlist
- Save/delete playlist
- Control: play/pause/next/prev/stop
- Show current song

## Options

Choose how dmenu is started:
```
mpd-select -d "dmenu -l 10"
```

or use [rofi](https://github.com/DaveDavenport/rofi), which works with multiple selections:
```
mpd-select -d "rofi -dmenu"
```

It is possible to select from custom playlists that are prefixed with a certain word. Say, you have a playlist ```music_bob_dylan``` and ```radio_wdr5```. Then you can specify ```music``` and ```radio``` as separate playlist selectors:
```
mpd-select -p music -p radio
```

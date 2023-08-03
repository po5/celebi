# celebi
This Pokémon restores properties from past sessions.

![celebi-small](https://github.com/po5/celebi/assets/42466980/aec4ca31-3bf8-433c-a4c0-9a2a09d1b255)

## Installation
Place celebi.lua in your mpv `scripts` folder.

## Usage
Specify properties to save in `script-opts/celebi.conf`, one per line.
```
volume=yes
sub-pos=yes
```
Data will be saved to `~~/celebi.txt` in a human-readable format and restored in future sessions.

## Why celebi?
It wanders across time, and also:
- Respects command line values
- Writes only when necessary
- Rate limits writes to be nice to your disk
- Allows saving of each property to be toggled at runtime
- Has the fastest init of any such script
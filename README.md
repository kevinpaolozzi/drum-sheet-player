# Drum Sheet Player

Shows drum notation one bar at a time, plays it back with synthesized drums and a click track, and lights up a top-down 4-piece kit to show what to hit.

- `drum-sheet-player.html` is the page source.
- `./build.sh` wraps it into `index.html`, which GitHub Pages serves.

Reading new sheet music from a photo only works when the page is opened inside Claude; the hosted copy plays the built-in sheets.

## Drum sounds

The drum recordings embedded in the page are from **Naked Drums** by Wilkinson Audio, in the [SFZ port by kinwie](https://github.com/sfzinstruments/WilkinsonAudio.NakedDrums), used under the [Creative Commons Attribution 4.0 licence](https://creativecommons.org/licenses/by/4.0/). Changes made: the direct and overhead mics are mixed to mono, trimmed, faded and encoded as MP3. If the recordings fail to decode, the page falls back to synthesized drums.

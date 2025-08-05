Please note that my fork is for personal use, it’s basically just a hardcoded tweak.

- Add `LoudnessEnhancer` and `setTargetGain` to 7000.
- No disk cache for the **video player** and **image**.
- Load only the **thumbnail image**. Avatar, banner etc. are blank.
- Expand comment.
- Expand title lines.
- Expand secondary controls.
- Minimum playback speed for gesture control is 1x.
- **No Captions** will not influence the next playback.
- Player controls do not auto-hide during playback.
- Pausing will exit fullscreen.

TODO: exoplayer RAM cache. Currently because of no disk cache, rewind always redownload.
TODO: Disk cache for video thumbnail (not seekbar) without okhttp cache? Currently only RAM cache.


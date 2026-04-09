# mpv-hold-to-reverse
An mpv script that changes the direction of the video (and audio) to "backward" when the "," key is held for 0.2 seconds and reverts it to "forward" when released.

You can already do this on mpv but it usually plays very, very, very slow. This script basically tells mpv to `--play-direction=backward`, which makes reverse playback smoother.

## 📦 Installation

Place [hold-to-reverse.lua](https://github.com/iiiGerardoiii/mpv-hold-to-reverse/raw/refs/heads/main/hold-to-reverse.lua) in your mpv `scripts` folder

Example:

- **Linux/Unix/Mac:** `~/.config/mpv/scripts/hold-to-reverse.lua`
- **Windows:** `%APPDATA%\mpv\scripts\hold-to-reverse.lua`

  (See the [Files section](https://mpv.io/manual/master/#files) in mpv's manual for more info.)

## 🖱️Usage

Just press and hold the "," key, it's that simple.

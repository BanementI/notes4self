# notes4self
Tools that I actually use. Like "random-repos" but not random.

# Data Hoarding
## Userscripts
### Instagram
[IG-Helper](https://github.com/SN-Koarashi/ig-helper/)

### Soundcloud / Bandcamp
[Stig's Art Grabber](https://greasyfork.org/en/scripts/20771-stig-s-art-grabr)

## Cover Art
[COV](https://covers.musichoarders.xyz/)

## Videos
[YT-DLP](https://github.com/yt-dlp/yt-dlp)

### YT-DLP Profiles
For windows, put this in %appdata%\yt-dlp\config

For Linux, put this in ~/.yt-dlp/config
* `--alias sc '--embed-metadata --embed-thumbnail -f hls_mp3_128'`
* `--alias arc '--embed-metadata --embed-thumbnail --download-archive archive.log --merge-output-format mkv --embed-subs --embed-chapters'`

Then you can use it like `yt-dlp --sc https://soundcloud.com/carbin3/drunk` and this will give you a mp3 with embedded cover art and metadata. You can adapt these into functions and source them in your .bashrc.
![2024-10-25_15-28](https://github.com/user-attachments/assets/5c543c6e-3da3-4431-8d73-148941f75860)

## Images
* [Gallery-DL](https://github.com/mikf/gallery-dl/) - Your best friend.

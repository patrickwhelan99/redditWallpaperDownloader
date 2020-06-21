# Need a new desktop wallapaper? Automate it! 


<p align='center'>
  <img src="https://img.shields.io/static/v1?label=Maintained&message=Yes&color=success"/>
  <img src="https://img.shields.io/github/issues/patrickwhelan99/redditWallpaperDownloader"/>
  <img src="https://img.shields.io/github/forks/patrickwhelan99/redditWallpaperDownloader"/>
  <img src="https://img.shields.io/github/stars/patrickwhelan99/redditWallpaperDownloader"/>
<p/>

<p align='center'>
  <img src="https://img.shields.io/github/license/patrickwhelan99/redditWallpaperDownloader"/> 
  <img src="https://img.shields.io/static/v1?label=Made%20With&message=Bash&color=informational"/>
<p/>


## Requirements
#### Core-utils
#### Util-linux

## Usage
```bash
./wallpaper -l links 
./wallpaper -r trippy
./wallpaper -l links -f -q
```

<p>

&#9;-l:	Filename to take links from

&#9;-r:	Specify a single subreddit to download from

&#9;-q:	Enables quiet mode

&#9;-f:	Use feh instead of gnome-shell

<p/>


## set up a crontab

```bash
crontab -e

@hourly /home/user/.scripts/wallpaper_setter/wallpaper -l /home/user/.scripts/wallpaper_setter/links -q
```

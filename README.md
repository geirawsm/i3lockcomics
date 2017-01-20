# i3lock-comics
Python script to fetch the newest edition of a comic strip and use it in i3lock. *Highly* inspired by [xkcd-lock](https://github.com/angs/xkcd-lock) by [@angs](https://github.com/angs).

&nbsp;

![Screenshot](https://cloud.githubusercontent.com/assets/265139/21699961/50057f3a-d39e-11e6-9825-b7f561e9cc14.png)

&nbsp;

## Short description

This script gets the latest strip of a comic which is added on top of a pixelated screenshot of your desktop. This image is then used in i3lock.

Comics included:
- Lunch (no)
- Pondus (no)
- xkcd
- Dilbert

## How to use

Run the script like so: `./i3lock_comics.py lunch`
If you use multiple displays, the script will only place the comic strip on your primary screen.

Only tested in Arch Manjaro i3 4.8.15-1, but should work on others as well as long as the dependencies is in place.


## Dependencies:
- i3lock v2.8
- scrot v0.8
- curl (called by the subprocess module)
- pendulum v0.8.0
- requests v2.12.4
- screeninfo v0.2.1
- PythonMagick v0.5
- beautifulsoup4 v4.5.3
- html5lib

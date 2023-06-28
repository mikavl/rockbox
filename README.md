# Rockbox

This repository holds my Rockbox configuration and theme for iPod Classic (yes, still in use).

## Theme

The WPS configuration in `simple.wps` shows a big album cover image and (scrolling) title, artist, album and date info.

![Screenshot](/wps/dump-220214-202112.png)

## Syncing from Git Bash

For my reference later, as I no longer use WSL.

1. Get `rsync` and its dependencies from [the MSYS2 repository](https://repo.msys2.org/msys/x86_64/) and place them in Git Bash's `/usr/bin`
2. Sync the files with `rsync --verbose --delete --modify-window=2 --update --recursive --omit-dir-times /source/drive/letter/Music/ /destination/drive/letter/Music`

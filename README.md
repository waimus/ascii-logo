# ASCII Logos
Various logos converted to ASCII art using `jp2a`. You can use this in Neofetch.

## Usage with Neofetch
Default:
```sh
neofetch --ascii /path/to/file.txt
```
With colours, assigned numbers refer to colour pallete of your terminal (0-15). See [Neofetch wiki page](https://github.com/dylanaraps/neofetch/wiki/Custom-Ascii-art-file-format) to find detailed manual.
```sh
neofetch --ascii /path/to/file.txt --ascii_colors 1 2 3 4 5 6
```
---
Example with `lp.txt` where it has 2 colours, hence put 2 colours to `--ascii_colors`:
```sh
neofetch --ascii ~/.ascii/lp.txt --colors 4 6 2 12 --ascii_colors 4 15
```
<p align="center">
  <img width="90%" src="./img/neofetch.png" />
</p>

## Notice
All rights of the logo belong to the respective owner.

# vim-colors-bionik
A light vim colorscheme with green comments and familiar keyword colors.

![screenshot](Screenshot.png)
Terminal on the left with corresponding ANSI colors set; GUI vim on the right.

## Goals
* light color scheme
* green comments
* familiar keyword colors 
    - similar to light Xcode and Visual Studio 2010
* uses italic, bold and underlined in the terminal
* terminal support
    - uses the (16) ANSI colors as defined by the terminal
    - tries to provide a good experience on a variety of selected colors
* GUI support
    - uses the colors noted below if used in a GUI vim

## Recommendations
### Font
Use a font with real italic letters like
* [Mononoki](http://madmalik.github.io/mononoki/)
* [Monofoki](https://github.com/datMaffin/monofoki) (modified Mononoki)
* Consolas
* [Fantasque Mono](https://github.com/belluzj/fantasque-sans)
* [Inconsolata LGC](https://github.com/MihailJP/Inconsolata-LGC/releases)

### Terminal Colors

Use for the background white `#ffffff` and for the foreground black `#000000`

| ANSI Code | Color                     | used by the colorscheme |
|-----------|---------------------------|-------------------------|
| 0         | Black: `#252525`          | no                      |
| 1         | Red: `#e60000`            | yes                     |
| 2         | Green: `#00b800`          | yes                     |
| 3         | Yellow: `#e66e00`         | yes                     |
| 4         | Blue: `#0a5594`           | yes                     |
| 5         | Magenta: `#b30070`        | yes                     |
| 6         | Cyan: `#00986a`           | yes                     |
| 7         | White: `#cccccc`          | yes                     |
| 8         | Bright Black: `#7f7f7f`   | no                      |
| 9         | Bright Red: `#ff3236`     | no                      |
| 10        | Bright Green: `#34ee34`   | no                      |
| 11        | Bright Yellow: `#ffa552`  | yes                     |
| 12        | Bright Blue: `#428ecf`    | yes                     |
| 13        | Bright Magenta: `#ec4fb1` | no                      |
| 14        | Bright Cyan: `#42d0a5`    | yes                     |
| 15        | Bright White: `#ededed`   | yes                     |


## FAQ
* [Italic in iTerm.app and tmux](https://medium.com/@dubistkomisch/how-to-actually-get-italics-and-true-colour-to-work-in-iterm-tmux-vim-9ebe55ebc2be): Without the "Configure vim" chapter;  `set termguicolors` has nothing to do with the italics.

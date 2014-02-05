dircolors
=========

Based upon the work of Ethan Schoonover and Sebastian Tramp.

Using the Solarized color scheme, colorize the output of `ls(1)` for
both GNU and BSD (OS X) systems.

Usage
-----

### GNU ls
`eval $(dircolors dircolors-dark)`
or
`eval $(dircolors dircolors-light)`


### BSD ls
```
LSCOLORS='exfxcxdxbxegedabagacad'
export LSCOLORS
CLICOLOR=yes
export CLICOLOR
```

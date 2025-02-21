# dwm
## About
dwm is a dynamic window manager for X. It manages windows in tiled, monocle and floating layouts. All of the layouts can be applied dynamically, optimising the environment for the application in use and the task performed.

These are my personal patches for it.
## Switching themes
At the start of config.def.h, include your desired theme from the themes folder. Example:
`#include "/home/stvka/git/suckless/dwm/themes/void.h"`

After that comment out the following lines:
```C
static const char col_gray1[]       = "#222222";
static const char col_gray2[]       = "#444444";
static const char col_gray3[]       = "#bbbbbb";
static const char col_gray4[]       = "#eeeeee";
static const char col_cyan[]        = "#005577";
```

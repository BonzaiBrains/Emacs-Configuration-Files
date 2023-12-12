# Installation

## Dependencies:

Programms to install via your package manager: 
* GNU Emacs
* git

> **Note:** Depending on your OS, when emacs is first installed it may generate `~/.emacs`, remove the generated default .emacs and clone this repository into ~/.emacs.d/

When you open Emacs for the firstime execute the following, 

> **Note:** `M-x` translates to `alt` `x`

```
M-x package-refresh-contents
M-x package-install RET evil RET
```

# Use

This configuration comes with:
* ViM keybindings
* Mouse support

> **Note:** Make fixes, changes and forks as you need.

> **Note:** Consider appending an alias in your `~/.bashrc` configuration(or for your prefered shell).
> ```
> alias emacs = "emacs -nw"
> ```
 


# Minimal Theme

A minimal theme based on xterm-256 color set.

Im not a big fan of syntax highlighting! to me, syntax highlighting is not 
only reduce code readability, but its also a distraction! of course many
programmers may not agree with this opinion, but for those who does,
this color theme is a **VERY** minimalistic color theme which use xterm-256 color set
so it has a unified look in both GUI and in Terminal.
it comes in two versions: `dark`, and `light`.

## Installation

Just place these files somewhere in you Emacs' `load-path`, and add them in your `init.el`:

    (load-theme 'minimal-dark t)
    ;or
    (load-theme 'minimal-light t)

also remember that if you want to use this theme in terminal, add this line to your `.bashrc`:

    export TERM="xterm-256color"

# License:

Use of this source code is governed by the 'Revised BSD License'
which can be found in the LICENSE file.


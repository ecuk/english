# english qwerty
English Qwerty keyboard layout for macOS

This is an English Qwerty keyboard layout for authors instead of programmers, and it is better suited to writing than the standard layout. It is based upon the standard macOS British keyboard layout with the following changes:

- [ and ] generate inverted commas ‘ and ’
- { and } generate double inverted commas “ and ”
- [ and ] are option-[ and option-]
- { and } are option-shift-{ and option-shift-}
- § and ± map instead to whitespace characters

Roughly, the [ and ] keys have had their standard option- and non-option- bindings swapped, although for some unfathomable reason Apple originally put the single inverted commas on one key (with and without shift) and the double inverted commas on the key next to it, whereas all other pairs of open- and close- delimiters are on keys next to each other. To me this layout makes much more sense.

As for the whitespace characters on the otherwise underused § and ± key:

- no-break space without modifiers
- thin space with shift
- hair space with option
- em space with option-shift

## Installation
To install:

`cp -rp English.bundle ~/Library/Keyboard\ Layouts/`
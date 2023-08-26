# My custom `.keylayout` files

This repository contains customized "Russian - Phonetic" keyboard layout in `.keylayout` format, for use on Mac OS X. Layout was modified to allow entering Cyrillic symbols like it's done in [LetterZu](http://www.letterzu.com/) application for MS Windows.

Here are some example of input transformations that are made (entered symbols -> displayed symbols):
* "zh" -> "ж"
* "sh" -> "ш"
* "ch" -> "ч"
* etc.

## How to install a new keyboard layout

1. Copy the `.keylayout` and `.icns` files to the `Keyboard Layouts` folder within `/Library` or `~/Library`.
2. Reboot, or log out and log in again.
3. Enable the new keyboard layout "Russian - LetterZu" via _System Preferences_ › _Language & Text_ › _Input Sources_.

Mac OS X has supported `.keylayout` files since version 10.2 (Jaguar).

## Credits

Created using [Ukelele.app](http://scripts.sil.org/ukelele).

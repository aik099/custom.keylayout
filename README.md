# My custom `.keylayout` files

This repository contains customized "Russian - Phonetic" keyboard layout in `.keylayout` format, for use on Mac OS X. Layout was modified to allow entering Cyrillic symbols like it's done in [LetterZu](http://www.letterzu.com/) application for MS Windows.

Here are some example of input transformations that are made (entered symbols -> displayed symbols):
* "zh" -> "ж"
* "sh" -> "ш"
* "sx" -> "щ"
* "ch" -> "ч"
* etc.

Use the [Ukelele.app](http://scripts.sil.org/ukelele) app to modify the provided keyboard layout to suite your needs.

## How to install a new keyboard layout

1. copy the `.keylayout` and `.icns` files to any folder of these depending on the purpose:
   * for all users: the `/Library/Keyboard Layouts`;
   * for current user only: the `~/Library/Keyboard Layouts` folder;
2. log out and log in again or reboot
3. enable the new "Russian - LetterZu" keyboard layout:
   1. go to the `Keyboard` section within the `System Settings` app
   2. scroll to the `Text Input` subsection
   3. click the `Edit..` button of the `Input Sources` setting to add/delete the input sources
   4. click the `+` icon in the bottom left corner
   5. choose the `Others` category on the left
   6. choose the `Russian - LetterZu` keyboard layout on the right
   7. click the `Add` button to add new keyboard layout
   8. click the `Done` button to close the `Input Sources` popup

Mac OS X has supported `.keylayout` files since version 10.2 (Jaguar).

## Credits

Created using [Ukelele.app](http://scripts.sil.org/ukelele).

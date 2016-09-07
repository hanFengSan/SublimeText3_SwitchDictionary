# SublimeText3 SwitchDictionary - ALPHA STAGE
## WARNING
This plug-in is still in active development!

## About
It is a tiny [Sublime Text 3](https://www.sublimetext.com/3) plug-in, **not tested** on [ST 2](https://www.sublimetext.com/), that add commands and shortcuts to switch between: no spell-check, spell-check for *French*, and spell-check for *English*.

*Note:* it will soon be better, allowing you to define your own list of dictionaries.

## Commands
### `enable_english_spellcheck`
  - It enables shell-check, and sets the dictionary to *English*
  - [It is binded](Default.sublime-keymap) to the key chain <key>ctrl+k, ctrl+e</key>

### `enable_french_spellcheck`
  - It enables shell-check, and sets the dictionary to *French*
  - [It is binded](Default.sublime-keymap) to the key chain <key>ctrl+k, ctrl+f</key>

### `switch_spellcheck`
  - It cycles between *English*, *French*, and *None*
  - [It is binded](Default.sublime-keymap) to the key chain <key>ctrl+k, ctrl+s</key> and also to <key>ctrl+alt+s</key>

### `disable_spellcheck`
  - It disables shellcheck
  - It is NOT binded to any key

----

## Accessing commands through...
### :notebook: The *Command Palette*
Press <key>ctrl+shift+p</key> (Windows, Linux) or <key>cmd+shift+p</key> (OS X) to open the *Command Palette*, and then search for:

 - `Switch Dictionary: to English`,
 - `Switch Dictionary: to French`,
 - `Switch Dictionary: None ↔ French ↔ English`.

### :mouse: The *Encoding Menu*
In the status bar, you should have a menu showing the encoding of the current file (by default it is `UTF-8`).
Click on the menu, and you can *click* on:

 - `Switch Dictionary – to English`
 - `Switch Dictionary – to French`
 - `Switch Dictionary – None ↔ French ↔ English`

### :musical_keyboard: Shortcuts
[By default](Default.sublime-keymap), the following shortcuts are available

 - <key>ctrl+k, ctrl+e</key> : `Switch Dictionary – to English`
 - <key>ctrl+k, ctrl+f</key> : `Switch Dictionary – to French`
 - <key>ctrl+k, ctrl+s</key>, <key>ctrl+alt+s</key> : `Switch Dictionary – None ↔ French ↔ English`


----

## :question: How to install it ?
### :ok_hand: With [Package Control](https://packagecontrol.io/)
If you have [Package Control](https://packagecontrol.io/) installed in Sublime Text 2/3, just press <key>ctrl+shift+p</key> (Windows, Linux) or <key>cmd+shift+p</key> (OS X) to open the *Command Palette*.

Start typing `install` to select `Package Control: Install Package`, then search for `SwitchDictionary` and select it. That's it!

You can check it was well installed by hitting <key>ctrl+k, ctrl+s</key> (it should enable English spell checking)

### :floppy_disk: Manually, with [git](https://git-scm.com/)
You can also install this package manually by entering the Packages directory of Sublime Text 2/3 and issuing on a terminal:

    git clone https://github.com/Naereen/SublimeText3_SwitchDictionary

----

## :boom: TODO
- Publish it on [Package Control](https://packagecontrol.io/) !
- Find a nice way to install it locally? Or is it FIXED already?

## :hourglass: Future Features
- Be more general: allow users to define manually a list of dictionary (path, and name), and add one command for each dictionary, and make the switch_spellcheck command cycle between them!

----

### :scroll: License
This plug-in is published under the terms of the [MIT license](http://lbesson.mit-license.org/) (file [LICENSE.txt](LICENSE.txt)).
© [Lilian Besson](https://github.com/Naereen), 2016.

[![Ask Me Anything](https://img.shields.io/badge/ask%20me-anything-1abc9c.svg)](https://github.com/Naereen/ama)
[![Analytics](https://ga-beacon.appspot.com/UA-38514290-17/github.com/Naereen/SublimeText3_SwitchDictionary/README.md?pixel)](https://github.com/Naereen/SublimeText3_SwitchDictionary/)

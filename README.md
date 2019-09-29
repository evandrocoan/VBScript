# VBScript package for Sublime Text [![Build Status](https://travis-ci.org/SublimeText/VBScript.png?branch=master)](https://travis-ci.org/SublimeText/VBScript)

This VBScript package for [Sublime Text](http://www.sublimetext.com/) adds:
- syntax highlighting
- snippets
- build configuration

## Credits
Original author: [Thomas Aylott](http://svn.textmate.org/trunk/Bundles/ASP_vb_NET.tmbundle/).

## Screenshots

![Espresso](https://raw.githubusercontent.com/SublimeText/VBScript/master/screenshots/espresso.png)
![Monokai](https://raw.githubusercontent.com/SublimeText/VBScript/master/screenshots/monokai.png)


## Installation

### By Package Control

1. Download & Install **`Sublime Text 3`** (https://www.sublimetext.com/3)
1. Go to the menu **`Tools -> Install Package Control`**, then,
   wait few seconds until the installation finishes up
1. Go to the menu **`Tools -> Command Palette...
   (Ctrl+Shift+P)`**
1. Type **`Preferences:
   Package Control Settings – User`** on the opened quick panel and press <kbd>Enter</kbd>
1. Then,
   add the following setting to your **`Package Control.sublime-settings`** file, if it is not already there
   ```js
   [
       ...
       "channels":
       [
           "https://raw.githubusercontent.com/evandrocoan/StudioChannel/master/channel.json",
           "https://packagecontrol.io/channel_v3.json",
       ],
       ...
   ]
   ```
   * Note,
     the **`https://raw...`** line must to be added before the **`https://packagecontrol...`**,
     otherwise you will not install this forked version of the package,
     but the original available on the Package Control default channel **`https://packagecontrol...`**
1. Now,
   go to the menu **`Preferences -> Package Control`**
1. Type **`Install Package`** on the opened quick panel and press <kbd>Enter</kbd>
1. Then,
   search for **`VBScript`** and press <kbd>Enter</kbd>

See also:
1. [ITE - Integrated Toolset Environment](https://github.com/evandrocoan/ITE)
1. [Package control docs](https://packagecontrol.io/docs/usage) for details.


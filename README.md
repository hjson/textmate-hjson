# TextMate compatible Syntax for Hjson

A lot of editors support TextMate compatible syntax definitions. You can use this package to install Hjson syntax highlighting support.

## IntelliJ Installation

- Install TextMate bundles support
  (if it is not installed already)
  - Open Preferences/Plugins
  - Click *Install JetBrains plugin...*
  - Type "textmate" in the search box
  - Install "TextMate bundles support"
  - Restart IntelliJ

- Install Hjson syntax
  - clone or download this repo
    `git clone https://github.com/hjson/textmate-hjson.git`
  - Open Preferences/Editor in IntelliJ
  - Select *Textmate Bundles*
  - Click on *+* and select the `textmate-hjson` folder
  - Depending on your color scheme you may wish to edit the mapping on the same screen (E.g. select something like *Dracula* if you are using a dark scheme)

- To install a custom color scheme
  - Create a subfolder named `Themes` in the `textmate-hjson` folder
  - Download your favorite tmTheme file to the folder you just created
  - You may need to restart/re-add the Hjson bundle
  - The theme should now show up in the mappings in *Textmate Bundles*

## Others

Check [Editor Support](http://hjson.org/download.html#ed) for a native package first (like Sublime/Atom/Visual Studio).

If your editor is not listed you may be able to install this package if it supports TextMate syntax bundles.

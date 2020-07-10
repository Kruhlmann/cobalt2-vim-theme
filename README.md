Cobalt2 Vim
===========

This fork contains a sensible cursor line color. It is now a slightly lighter version
of the background color, whereas before it was a eye-popping yellow.

It also changes the ColumnColor to the same color as the cursor line, from the original
black.

Install
-------

With [Plug](https://github.com/junegunn/vim-plug):

    Plug 'gertjanreynaert/cobalt2-vim-theme'

For terminal vim: the only way to accomplish the background color is by
installing the [cobalt2 iterm color
scheme](https://github.com/wesbos/Cobalt2-iterm/blob/master/cobalt2.itermcolors)

Installing xcode theme
----------------------

Download the Cobalt2.dvtcolortheme file

Create the destination folder for the theme

```
  mkdir ~/Library/Developer/Xcode/UserData/FontAndColorThemes
```

Copy the theme from Downloads folder to the xcode destination folder

```
  cp ~/Downloads/Cobalt2.dvtcolortheme ~/Library/Developer/Xcode/UserData/FontAndColorThemes
```

The colortheme must be an executable, which can be achieved by following command

```
  chmod +x ~/Library/Developer/Xcode/UserData/FontAndColorThemes/Cobalt2.dvtcolortheme
```

Restart xcode and the theme should be available in xcode preferences


License
-------

MIT

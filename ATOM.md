# ATOM: My Preferred Text Editor

While there are many text editors I am familiar with (NotePad++, Sublime, Dreamweaver, VIM, etc.) I prefer to code with ATOM. This is based on the flexibility that ATOM offers as a "hackable" editor. I could literally program in a package, if it did not already exist, to make the editor do what I want.

If you are new to ATOM, packages are like extensions in Firefox, or APT for Debian/Ubuntu systems. Packages add features to the editor. ATOM comes preinstalled with a core bundle of packages but to increase efficiency and conformity in my programming I have installed these packages: 

## Installed Packages
- Linter
  - Dependencies:
    - buys-signal
    - intentions
    - linter-ui-default
  - linter-php - lint PHP on the fly

- color-picker - a color picker for atom (right-click, or press cmd-shift-c/ctrl-alt-c to open)
- dbclick-tree-view - changes tree-view to only respond to double-clicks (helpful because it prevents large files opening on a single-click)
- docblockr - a helper package for writing documentation
- file-icons - assign icons and colors by extension (the package author states this is for, "improved visual grepping") :-)
- highlight-selected - highlights the currently selected word when double clicking
- minimap - a preview of the full source code (I love this one. It also offers "improved visual grepping" of my source code")
- minimap-cursorline - displays the current active line on the minimap
- minimap-pigments - displays pigments (color selections) in the minimap
- php-hyperlick - ctrl left-click on a class name, method or function and ATOM loads the file for editing
- pigments - displays the actual color specified by your code (RGBa, Hex, etc)
- remote-ftp - FTP/FTPS/SFTP
- tree-view-scope-lines - more visual grepping in the tree-view

## Packages to Avoid (CPU/Memory leeches)
These are great ideas, but their current versions have lagged out my computers and need some reworking before they would improve my coding experiences.
- minimap-lens (v0.2.0) - like a magnifying glass, it creates a popup when mousing-over the minimap. The popup shows your code at that location. In actuality this causes the editor to stop everything (even the cursor stops blinking) for a few seconds. Mildly infuriating after a while if your cursor accidentally goes over the minimap, or any time you want to scroll down with the vertical scrollbar.

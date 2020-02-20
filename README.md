# There Is No Spoon
An introduction to some dangerous assumptions while building software systems.

The format is a reveal.js presentation mastered in AsciiDoc 

## `./prepare`
Downloads reveal.js

## `./build`
Creates the presentation HTML

## `./watch_and_rebuild`

[Linux] Run the build when the file is saved.

Uses `inotifywatch` which may need to be installed
e.g. `sudo apt install inotify-tools`

## `./package`
ZIPs up the HTML + dependencies into a sharable archive

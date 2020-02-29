# command-not-found-void.zsh
Automatically search for missing commands in Void Linux repos with zsh.

This is an incredibly minor modification to the command-not-found.zsh for arch found at <a href="https://github.com/falconindy/pkgfile/blob/master/extra/command-not-found.zsh">falconindy/pkgfile</a>.
Basically I've substituted pkgfile with xlocate, and colorized the output with <a href="https://github.com/sohamkamani/supercat">supercat</a>.
This is trivial, but I like it and I figured I'd share it.

## Dependencies
* xtools
* supercat

## Installation
Source the file in your .zshrc and make sure everything is pointing to the right location.

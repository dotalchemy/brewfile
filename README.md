# Stu's Brewfile

## What?
Homebrew, or brew, is a package manager for MacOS X. It provides a convienient CLI interface for managing software installations and updates.

Effectively, it's `apt` / `yum` for Mac users, and it's _wonderful_.

For installation / usage documentation, refer to http://brew.sh/

If you just want to make `brew` exist as a thing on your Mac and head into the utopian future of textual package management with reckless abandon, pop the below into your terminal and press `enter`

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Best of luck, and Godspeed.

## Brewfiles?

A Brewfile, in conjunction with `brew bundle`, will go through and install everything defined in the Brewfile.

 - Wiped your Mac? Brewfile.
 - Bought a new Mac? Brewfile.
 - New coworker needs a quick jumpstart? Brewfile.

In this repo, you'll find my Brewfile. It isn't finished. It'll never be finished. A Brewfile is a living document reflecting the ever evolving state of your happy little OSX world. While the main purpose of my Brewfile is to ensure all of my Mac's have a consistent set of tools installed, I think we'd all be lying if we said the main point of a Brewfile was to drop it on Github then poke around at others and find neat new tools you'll use once and forget about.

## Usage

Drop the Brewfile into a directory, enter that directory in a terminal, and type...

```
brew bundle
```

Yeah, that's about it. You can also clone this and pull updates every so often if you want. Not that you would, as the whole point is to personalize your own Brewfile with what _you_ want, not what I want, unless what you and I want are the exact same thing, in which case we should be friends.

## No, want better please

Fine

https://homebrew-file.readthedocs.io/en/latest/index.html

`brew-file` will let you manage your Brewfile with more advanced features, such as syncing to cloud storage or Git repositories. 
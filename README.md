# Homebrew tap for termchat

[termchat](https://github.com/sw4p/termchat) lets you chat with a random individual on your local network, end-to-end encrypted, from the terminal.

## Install

```sh
brew install sw4p/termchat/termchat
```

This adds the tap and installs termchat in one step. Then run:

```sh
termchat
```

See the [termchat README](https://github.com/sw4p/termchat#readme) for usage, commands and the privacy model.

## Update

```sh
brew update
brew upgrade termchat
```

## Uninstall

```sh
brew uninstall termchat
brew untap sw4p/termchat
```

## Notes

- **Cask, not formula.** termchat is installed as a prebuilt binary from the [releases page](https://github.com/sw4p/termchat/releases), and Homebrew checks its SHA-256 checksum before installing.
- **Gatekeeper.** The binary isn't notarized by Apple, so the cask clears its quarantine flag after installing. Without that, macOS would refuse to run it.
- **Generated file.** `Casks/termchat.rb` is generated and updated automatically on every termchat release. Changes made to it by hand are overwritten by the next release.
- **Linux.** On Linux, the [install script](https://github.com/sw4p/termchat#install) or the `.deb`/`.rpm` packages are the recommended way to install.

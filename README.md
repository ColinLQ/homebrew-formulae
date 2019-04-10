# homebrew formulae

Repository for my own testing, or simple taps of programs that haven't been added to homebrew.

Included:  
- [Ghidra](http://ghidra-sre.org), a powerful static analysis tool
  - build process hasn't been released yet, so it can't be added as a homebrew formulae
  - doesn't bundle a .app, so can't be added as a Cask
- [libguestfs](http://libguestfs.org/), a library for editing VM disk images
  - should be added to homebrew after some options are tested/removed
- automake-1.15, (autotools)
  - this version was a build dep for older versions of libguestfs
- [matterhorn](https://github.com/matterhorn-chat/matterhorn) terminal mattermost client
  - i don't feel like building it from source right now
- [browserpass](https://github.com/browserpass/browserpass-native) native binary for browserpass web extension
  - homebrew-core won't accept as a formula since it works with an app (chrome/firefox), but it's not right for a cask

# homebrew formulae

My own homebrew repository, mostly for simple taps of programs that haven't been added to homebrew.

To use:
```bash
brew tap amar1729/formulae
brew install <formula>
```

Included:  
- [libguestfs](http://libguestfs.org/), a library for editing VM disk images
  - should be added to homebrew after some options are tested/removed
- automake-1.15, (autotools)
  - this version was a build dep for older versions of libguestfs
- [matterhorn](https://github.com/matterhorn-chat/matterhorn) terminal mattermost client
  - i don't feel like building it from source right now

- April 06, 2019: Ghidra added to homebrew-cask.
  - https://github.com/Homebrew/homebrew-cask/pull/59872

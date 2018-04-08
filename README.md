# Useful tools and resources I use

## Tools

* https://github.com/mateogianolio/sshync - Auto-sync files or directories over SSH. 
* https://github.com/b-ryan/powerline-shell - A beautiful and useful prompt for your shell (e.g. shows git status in the prompt)
* https://atom.io/ - extensible editor
  * TODO: Atom plugins list
* https://github.com/jupyterlab/jupyterlab - IPython and more on steroids
* https://github.com/tonsky/FiraCode - mono-spaced font with ligatures 
* https://justgetflux.com/ - shifts the colour of the screen to warmer tones after sunset (still more configurable than Night Shift)

### macOS specific tools
* https://itunes.apple.com/gb/app/systempal/id453164367?mt=12 - SystemPal shows CPU, network uses, etc. on the menu bar
* https://www.objective-see.com/products/oversight.html - OverSight monitors when microphone and camera get enabled
* https://iterm2.com/ - replacement of Terminal
* https://rowanj.github.io/gitx/ Git history viewer with branch trees (Note: After install, run from Applications and choose from GitX menu "Enable Terminal Usage" to create symlink to /usr/local/bin/gitx)
* https://brew.sh/ - Homebrew is an OSS package manager (run `brew analytics off` and `echo export HOMEBREW_NO_AUTO_UPDATE=1 HOMEBREW_NO_GITHUB_API=1 HOMEBREW_NO_INSECURE_REDIRECT=1 >> ~/.bash_profile` after install if you want more privacy)
* http://semaja2.net/ye-ol-projects/insomniaxinfo/ - InsomniaX prevents Mac Book Pro from sleeping - doesn't fully work on High Sierra apparently though:
```
# sudo kextload /Applications/InsomniaX.app/Contents/Resources/Insomnia_r11.kext
/Applications/InsomniaX.app/Contents/Resources/Insomnia_r11.kext failed to load - (libkern/kext) system policy prevents loading; check the system/kernel logs for errors or try kextutil(8).
```
* https://github.com/google/santa - A binary whitelisting/blacklisting system for Mac OS X
  * Simple lockdown configuration https://gist.github.com/0xmjk/cb9ca44135dc2307f39711ae3d4b42db
## Resources

* https://publicsuffix.org/ - DNS effective domains list

### macOS specific resources

* https://github.com/drduh/macOS-Security-and-Privacy-Guide - security and privacy guide for macOS
* http://docs.hardentheworld.org/OS/MacOS_10.12_Sierra/ - guide to hardening macOS Sierra


test_spriteunmask branch

This is a special build of FCEUX for making videos explaining the internal operation of the NES.

Under Config > Display you may normally turn off the BG layer to see just the sprites, but in this "unmasked" branch sprites that are hiding behind the background image are not hidde, so you can see these hidden ones too.

Usign gNoBGFillColor=255 in your FCEUX.cfg will also replace unrendered parts of the image with a unique key colour that may be useful for masking them, if trying to prepare overlays.

New PPU setting is required.




# fceux [![Build status](https://ci.appveyor.com/api/projects/status/github/TASVideos/fceux?branch=master&svg=true)](https://ci.appveyor.com/project/zeromus/fceux)

An open source NES Emulator for Windows and Unix that features solid emulation accuracy and state of the art tools for power users. For some reason casual gamers use it too.

## Builds and Releases

win32 autobuilds @ https://ci.appveyor.com/project/zeromus/fceux/build/artifacts

But you might like mesen more: https://github.com/SourMesen/Mesen 

You should get releases from here: https://sourceforge.net/projects/fceultra/files/

That's because github forces us to use tags we don't have for releases.

2.2.3 is the most recent release but most people are using the autobuilds.

# Core Audio Utility Classes - Archive

This repository serves as an archive for Apple's *Core Audio Utility Classes*, as available from [Apple](https://developer.apple.com/library/mac/#samplecode/CoreAudioUtilityClasses/Introduction/Intro.html).

The reason for the archive is that Apple usually drops support for older OSes. For example, the 1.03 version of the files are not supported for OX 10.6 or earlier, whereas the previous versions are (or might be; I'm not actually sure).

The ZIP files are verbatim downloads from Apple's web site. The PATCH files are required for clean compilations; you may safely ignore "applied with fuzz" warnings from the `patch` utility. Also, don't forget to use the `-p0` option to `patch` or you'll wonder why `patch` can't find the files it's looking for...

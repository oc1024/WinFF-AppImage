# WinFF-AppImage
This builds an AppImage out of the Qt4 version of WinFF located on Debian Stretch's repos.
This AppImage bundles FFMpeg in order to run on stock Ubuntu 16.04, as per AppImageHub's requirements.

If you want a lighter AppImage, add `ffmpeg` and `avconv` to the `exclude:` section in `winff.yml`
and use [Pkg2AppImage](https://github.com/AppImage/pkg2appimage/) to generate a new AppImage.

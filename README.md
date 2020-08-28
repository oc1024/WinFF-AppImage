# WinFF-AppImage
This builds an AppImage out of the Qt4 version of WinFF located on Debian Stretch's repos.
This AppImage does _not_ bundle FFMpeg or AVConv, which must be supplied by the host.
If you want it to, remove this section of the YAML file:
```
exclude:
    - ffmpeg
    - avconv
```
and use [Pkg2AppImage](https://github.com/AppImage/pkg2appimage/) to generate a new AppImage.

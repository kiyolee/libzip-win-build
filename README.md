# libzip-win-build

libzip Windows build with Visual Studio.

This version is libzip-1.5.1.

See win-build-info for general information about the
win-build effort.

To build, simply open the required solution file, and
you know how to use Visual Studio, right?
(or perhaps this is the wrong place for you.)

Depends on zlib-win-build, currently a hard reference assuming
zlib-win-build sits next to libzip-win-build.

Basically, in a command prompt:

> \> cd {somewhere}\\  
> \> git clone http://github.com/kiyolee/zlib-win-build.git  
> \> git clone http://github.com/kiyolee/libzip-win-build.git

Build zlib first and then libzip, with the same corresponding Visual Studio solution of course.

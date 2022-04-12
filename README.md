# libzip-win-build

libzip Windows build with Visual Studio.

This version is libzip-1.7.3.

To build, simply open the required solution file, and
you know how to use Visual Studio, right?
(or perhaps this is the wrong place for you.)

Depends on zlib-win-build. There are hard references assuming
zlib-win-build sits next to libzip-win-build.

Basically, in a command prompt:

> \> cd {somewhere}\\  
> \> git clone https://github.com/kiyolee/zlib-win-build.git  
> \> git clone https://github.com/kiyolee/libzip-win-build.git

Build zlib first and then libzip, with the same corresponding Visual Studio solution of course.

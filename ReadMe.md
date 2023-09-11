## WARNING

This repository exists because MSYS2 now uses FFMPEG 6.0 and I had to make it work for FFMPEG 6.0.
I have no fucking clue how to use FFMPEG (I spent less than a day making it compatible with it) so this code base might include a lot of mistake. My sole goal was making it compile and show a video on PSDK with SFML 2.6.

There's a huge chance this includes memory leaks or even stupid things since I couldn't get most of the logic of the stuff here.

If you want to fix all my silly mistakes, go on, it's welcomed!

## How to build (MSYS2)

```
ridk enable
cmake_msys2
make
```

You can figure out the deps using ProcMon (there's 85MB of them, it makes 30MB using upx).

See http://sfemovie.yalir.org/ for information on sfeMovie.

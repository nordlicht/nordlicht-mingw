# How to cross-compile *nordlicht* for Windows

This is only for dynamic linking, haven't figured out how to do a static build yet.

1. Be on Arch Linux.
2. For convenience, add the [mingw-w64](https://wiki.archlinux.org/index.php/Unofficial_user_repositories#mingw-w64) repository to pacman.
3. Install (at least) `mingw-w64-ffmpeg`, `mingw-64-popt`, and `mingw-w64-mman-win32-svn`.
4. Pray to the gods of cross-compiling.
5. Run `./compile`

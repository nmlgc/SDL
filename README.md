
Simple DirectMedia Layer (SDL for short) is a cross-platform library
designed to make it easy to write multi-media software, such as games
and emulators.

This fork adds WIP support for Windows 9x, which can be enabled by
defining the `__WIN9X__` macro on SDL's build command line. If you
use `SDL_Thread`s, it also must be defined prior to #including
`SDL_thread.h`.

You can find the latest release and additional information at:
https://www.libsdl.org/

Installation instructions and a quick introduction is available in
[INSTALL.md](INSTALL.md)

This library is distributed under the terms of the zlib license,
available in [LICENSE.txt](LICENSE.txt).

Enjoy!

Sam Lantinga (slouken@libsdl.org)

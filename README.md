![goro](https://avatars2.githubusercontent.com/u/40675644?s=460&v=4)


Website :

https://goro.info

-= Building Goro =-

On *nix:

Dependencies: GCC 4.7.3 or later, CMake 2.8.6 or later, and Boost 1.55 or later.

You may download them from:

http://gcc.gnu.org/

http://www.cmake.org/

http://www.boost.org/

Alternatively, it may be possible to install them using a package manager.

To build, change to a directory where this file is located, and run `make'. The resulting executables can be found in build/release/src.

Advanced options:

Parallel build: run `make -j<number of threads>' instead of `make'.

Debug build: run `make build-debug'.

Test suite: run `make test-release' to run tests in addition to building. Running `make test-debug' will do the same to the debug version.


On Windows:

Dependencies: MSVC 2013 or later, CMake 2.8.6 or later, and Boost 1.55 or later. You may download them from:

http://www.microsoft.com/

http://www.cmake.org/

http://www.boost.org/

To build, change to a directory where this file is located, and run this commands: (VisualStudio 2015)

mkdir build && cd build && cmake .. -G "Visual Studio 14 Win64" ..

then open goro.sln File on Visual Studio

In VS' Solution Explorer select upnpc-static' Properies -> C/C++ -> Code Generation -> Runtime Library - > change it to Multi-threaded (/MT)

And Finaly do the Build.

Good luck!


[Pool.goro.info](http://pool.goro.info)

[explorer.goro.info](http://explorer.goro.info)-This is the block explorer

[WEB WALLET](https://goro.info/wallet)


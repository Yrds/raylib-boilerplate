# raylib-boilerplate

## Objective

The main reason of this project is to provide a out-of-box environment to develop raylib games.

## Requirements


Raylib - https://www.raylib.com/.
CMake - https://cmake.org/install/.

I suggest try to install first in your distro package manager before searching from pre-build binaries/compiling.

## Cloning and building

```bash
git init myGame #make your own repo
cd myGame
git pull https://github.com/Yrds/raylib-boilerplate`
mkdir build
cmake ../
cmake --build .
./myGame #test
```

If you see a window with the text "Congrats! You created your fisrt window!", then it's everything ok

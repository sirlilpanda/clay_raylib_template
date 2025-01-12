# template

This is a simple standalone template to get up and running with clay using the raylib renderer.
the `CMakeLists.txt` handles globbing all the scource files together.
this template is currently only tested on windows with `minGW`.


# init

## windows

```ps1
> mkdir build
> cd build
> cmake ..
> cd ..
> cmake --build build/
# to run 
> .\build\clay_ui.exe
```
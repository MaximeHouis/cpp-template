# cpp-template
My C++ projects template :)

## Why

This is my basic structure that I use for my C++ projects. Feel free to use it if you like it.

I will make a conan version soon™.

## How

* Click on the big green `Use this template` button
* You can search for `template:` through files to access main code parts to change depending on your project
* Remove what you don't like
* Add stuff you like
* Do what the f\*ck you want, really

## What

* `.clang-format` for the style
* GitHub Action workflow to build the project
* CMake configurations, compiler warnings and cool flags
* lib/exe separation that is easily removable for executable-only projects
* Some C++ utility things I may need:
  * `ScopedProfiler`: Code profiling using RAII, useful for quickly benchmarking code without using big profilers. (you should still profile your code with normal profilers!)
  * *Maybe more in the future?*
* `.gitignore` to exclude unwanted files/dirs

## License

The license in the template files is *Apache License 2.0* (it's the one I use the most for my projects), **but this template itself is public domain**, so feel free to do whatever you want with this.

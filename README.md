# CMake_Projects

>> This repo contains an example project of CMake.

## CMake commands
- Generate Visual Studio project files: cmake -G "Visual Studio 17 2022" .  //  cmake -S . -B build/
- Build the project: cmake --build .

Unsorted commands:
## cmake ..
## cmake --build .
## to run executable: $ ./cmake_main
## $ make -> also runs cmake for us

# Some helping commands
>> ldd <project name>    -> example $ ldd cmake_main

# 'cmake ..' not working -> '-- Check for working C compiler: /usr/bin/cc - broken'
    -> sudo apt-get install build-essential

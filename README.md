# CMake_Projects

>> This repo contains an example project of CMake.

## CMake commands
### Window
- Generate Visual Studio project files: cmake -G "Visual Studio 17 2022" .  //  cmake -S . -B build/
- Build the project: cmake --build .

### Linux
> make version: GNU Make 4.3
> cmake version: 3.22.1
> cmake generator: Unix Makefiles
> C compiler: GNU 11.4.0

#### Simple Commands
- Go to project folder with c-codes and CMakeFiles.txt
- create build folder: § mkdir build
- go to build folder: § cd build
- generate build files: § cmake ..
- create executable: § make
- Run App: § ./hello_world

#### Commands with flags and more
- Generate build files: § cmake -S . -B build/
- Go to build/ and: § make
- Run executable: § ./HelloWorld

Unsorted commands:
## cmake ..
## cmake --build .
## to run executable: $ ./cmake_main
## $ make -> also runs cmake for us

# Some helping commands
>> ldd <project name>    -> example $ ldd cmake_main

# 'cmake ..' not working -> '-- Check for working C compiler: /usr/bin/cc - broken'
    -> sudo apt-get install build-essential

# Sayers.SDL2.Core
Nuget package for handling SDL2-CS bindings and the native SDL dlls.

The bindings are provided by flibitijibibo here: https://github.com/flibitijibibo/SDL2-CS

All of the licenses for the various SDL dlls can be found in the `licenses` folder.

# Usage
To use, either install `Sayers.SDL2.Core` through the nuget package manager or with:
```
dotnet add package Sayers.SDL2.Core --version 1.0.11
```

You'll also need to allow `Unsafe code` in order to actually use the bindings. This can be found by right-clicking on your Project > Properties > Build > General > `Allow code that uses the 'unsafe' keywaord to compile.`

![image](https://user-images.githubusercontent.com/8796296/151873209-f8f34003-e40c-4cae-a29d-2185c21c335a.png)

# Getting Started
Tutorials going in depth on the usage SDL2-CS can be found here: https://jsayers.dev/tutorials/

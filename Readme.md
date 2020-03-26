# Conan NlohmannJson

![Build status](https://github.com/rgpaul/conan-nlohmann-json-scripts/workflows/Linux/badge.svg)

This repository contains a conan receipe that can be used to build a nlohmann json package.

For Infos about the library please visit [Github](https://github.com/nlohmann/json).  
The library is licensed under the [MIT License](https://github.com/nlohmann/json/blob/master/LICENSE.MIT).  
This repository is licensed under the [MIT License](LICENSE).


## macOS

To create a package for macOS you can run the conan command like this:

`conan create . nlohmann-json/3.7.3@rgpaul/stable`

### Requirements

* [CMake](https://cmake.org/)
* [Conan](https://conan.io/)
* [Xcode](https://developer.apple.com/xcode/)

RAPNGAsm dependency BuildPack for Heroku
========================================

Provides the dependencies to build the native extensions for RAPNGAsm during a Heroku Ruby bundle.

Dependencies provided are:
 * libarchive
 * Boost
 * CMake
 * apngasm / libapngasm
 * SWIG

Installing
----------
```heroku buildpacks:add https://github.com/Kagetsuki/heroku-rapngasm-buildpack.git```

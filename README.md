OpenCL Simple Test
===============

This site contains two simple OpenCL programs: *Transmisson* and *Endianness*.
Both programs could be built on multiple platforms, such as
iOS (clang), Mac OS X (clang) and Windows (MSVC) etc.

There is also a Makefile for iOS to build. 
And the Darwin ARMv7 binaries are already built here named *Transmisson* and *Endianness*.

##Transmisson
This demo simply transmits data between internal RAM and GPU RAM and calculates the time it costs. It is a four-step progress:

* Internal RAM to Internal RAM
* Internal RAM to GPU RAM
* GPU RAM to GPU RAM
* GPU RAM to Internal RAM

The data size of the demo is 8 mega bytes.

##Endianness
This demo converts the endianness of unsigned 64-bit integers.

The number of integers are 32768.

##iOS Makefile Usage
You have to specify your SDK path before using it. The default SDK is __Xcode 5.0 with iOS 7.0 SDK__.

#Declaration
This site is distributed under BSD license.

Linus Yang

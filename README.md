# Z80Explorer
Visual Zilog Z-80 netlist-level simulator

Z80 Explorer is a Zilog Z80 netlist-level simulator capable of running Z80 machine code and also an educational tool with features that help reverse engineer and understand this chip better.

Application's User's Guide: https://baltazarstudios.com/Z80ExplorerGuide/
<br>
It is also described in a blog: https://baltazarstudios.com/z80explorer
<br>
A brief overview is on YouTube: https://youtu.be/_dyngzTEnvw

## Before you run it

Read the User's Guide.<br>
The application is separate from the Z80 resources that it uses. This matters only if you are building it yourself; if you are using a pre-built package, the resources are included and don't need to be downloaded separately.<br>
Download Z80 resources from here: https://github.com/gdevic/Z80Explorer_Z80<br>
Extract two 7z files: “layermap.7z” and “segvdefs.7z”. On Windows, use any of the many 7z utilities and on Linux, use “p7zip -d layermap.7z”.<br>
Then, read the User's Guide.<br>

![Z80 Explorer](https://baltazarstudios.com/wp-content/uploads/2020/07/z80explorer-app.png)

## Getting a pre-built binary (Windows)

A pre-built binary for Windows can be found in the release section of github here:<br>
https://github.com/gdevic/Z80Explorer/releases

## Compiling from sources

The application is built on the Qt framework.

* On Windows, install MS Visual Studio 2015 (+latest Service Pack, Update3). On Linux, gcc will do.
* Install Qt 5.15.0 framework (with support for x64 MS Visual Studio 2015 on Windows).
* Add the “Qt Script (deprecated)” component to the Qt installation.
* Compile with QtCreator selecting the “Release” build.



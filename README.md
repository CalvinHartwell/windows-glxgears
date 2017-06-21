# glxgears for Windows - OpenGL Demo & Benchmark Tool

This repo is a windows port of the common unix opengl application glxgears.

Glxgears is a common tool for testing the OpenGL rendering pipeline and gives a simple fps benchmark from the gears animation.

This particular port is compiled in Visual Studio 2017 and it should be very easy to upgrade this project for newer versions of visual studio. 

Unfortunately this tool is now very dated - it makes use of the old style OpenGL fixed rendering pipeline which has been deprecated for a long time (https://www.opengl.org/wiki/Fixed_Function_Pipeline).

A more modern approach would be to use things like shaders - the rendering pipeline is actually emulated with shaders as of 2.0+

If ported, this application may not work correctly with the OpenGL-ES specification (mobile devices).

The original glxgears application was written by Brian Paul in 1999-2001 his license/warranty is provided within the source-code.

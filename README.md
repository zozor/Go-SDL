Go-SDL
======

Go-SDL provides bindings for the [SDL][sdl], [SDL_image][sdl-image], [SDL_mixer][sdl-mixer], and [SDL_ttf][sdl-ttf] libraries.

Prerequisites
-------------

 * A version of [Go][go] compatible with weekly.2011-02-07
 * [SDL][sdl]
 * [SDL_image][sdl-image]
 * [SDL_mixer][sdl-mixer] (For *mixer* package only)
 * [SDL_ttf][sdl-ttf] (For *ttf* package only)

Installation
------------

To install all of the relevant libraries, use the following:

    go get github.com/banthar/Go-SDL/sdl

Usage
-----

To import, use the following:

    import "github.com/banthar/Go-SDL/sdl"

Replace the final 'sdl' with the library that you want to import.

Credits
-------

 * [banthar](https://github.com/banthar)
 * Kevin MacLeod (*mixer* test music)

[go]: http://www.golang.org
[sdl]: http://www.libsdl.org
[sdl-image]: http://www.libsdl.org/projects/SDL_image/
[sdl-mixer]: http://www.libsdl.org/projects/SDL_mixer/
[sdl-ttf]: http://www.libsdl.org/projects/SDL_ttf/

<!--
    vim:ts=4 sw=4 et
-->

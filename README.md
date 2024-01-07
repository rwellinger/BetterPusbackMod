# About BetterPushback Mod X-Plane 12

This is a pushback plugin for the X-Plane 12 flight simulator.
It provides an overhead view to plan a pushback route and
accomplishes a fully automated "hands-off" pushback, letting the user
focus on aircraft startup and other pilot duties during pushback. It can
of course also tow you forward, or perform any arbitrarily complicated
pushback operation. To increase immersion, it speaks to you in a variety
of languages and accents, simulating ground staff at various places
around the world.

### About this Fork and Copyright

Better Pushback is developed by "Saso Kiselkov". So if you see this project or else, just contact me.
I just did it, to "keep it a life on X-Plane 12". I will always respect that this is your code,
and you are the father of this application. Hope you accept this as there was no answer from your side.

There is no idea to steal it from you. If you don't like this effort. Just say and I will stop it, no question.

Thanks

### Acceptance

If you do not accept this "modified" Better Pushback, then please don't use this one, use just the original version.
You can found it here...

https://github.com/skiselkov/BetterPushbackC


## Downloading BetterPushback

You can get the last binary release from here:

https://forums.x-plane.org/index.php?/files/file/89033-better-pushback-mod-x-plane-12/


Some Beta / Pre-Releases can be found here:

https://github.com/rwellinger/BetterPusbackMod/releases

(Please be aware that the pre release maybe still has some issues inside and maybe is not final tested.)

## Support if you like what we did:

https://www.paypal.com/donate/?hosted_button_id=NGZPRYALBDJU4

(Please note that this plugin will remain open-source.)


## Building BetterPushback

To build BetterPushback yourself you need either a Linux or a Mac
machine. The Windows version is built through cross-compiling from Linux.
For the pre-requisites on each platform, see `qmake/build-win-lin` or
`qmake/build-mac`. Once you have everything installed, run the script
labeled `build_release` from this directory. It drives the build and
compiles everything as necessary.

For details on how to add tug liveries, see
`objects/tugs/LIVERIES_HOWTO.txt`.

To add a voice set, see `data/msgs/README.txt` for the information.

### libacfutils Library Required

I removed from the project. It need to by downloaded separatly. To make sure you have a matched version, take the fork in my repository.
To connect with the library setup the Library in the "CMakeLists.txt" File in the "src" directory.

file(GLOB LIBACFUTILS "../../../libs/libacfutils")

As I found out in the last view days the relation to this library are very hard and many issues come from here ... it is not possible to splitup the library.

The library can be found here:
https://github.com/skiselkov/libacfutils

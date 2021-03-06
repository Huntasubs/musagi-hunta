===========
Musagi-hunta
===========
Musagi-hunta is (hopefully) a continuation of stqn's work to bring this wonderful little editor to linux, updating it (if necessary?) and maybe bringing it into the 64bit world. 


===========
Musagi-stqn
===========

Musagi is a music creation tool originally written by DrPetter for Windows.
Musagi-stqn is my attempt at providing a working version for Linux.

Credits:
--------
- Original Musagi 0.23 for Windows by DrPetter (Tomas Pettersson)
- Original Musagi 0.1 SDL/Linux port by pekuja (Pekka Kujansuu, <pekuja iki fi>)
- Merging of original SDL/Linux port and Musagi 0.23 source code,
  and additionnal work by stqn (Olivier Fabre, <off free fr>)
- PortAudio v19 support by spctrl and drasish.

Licence:
--------
- See license.txt.

Target platforms:
-----------------
- This version of Musagi uses the following cross-platform libraries and should
  work on any platform supporting them with minimal work:
  - SDL
  - OpenGL
  - GTK+ 2
  - PortAudio v19
- It was built and tested under Linux x86 (32 bit) only.
- 64 bit support is currently non-existent due to many problems throughout the
  source code.

Done in this version:
---------------------
- See the NEWS file for the history.

Things missing compared to Musagi 0.23 for Windows:
---------------------------------------------------
- MIDI
- VST
- Joysticks support
(I don't need them, have no idea what they're for, and don't know how much work
it would be to make them work.)

Warnings:
---------
- There are no confirmation requesters whatsoever.
- There is no undo.
- The program might crash, so save often and use different file names for
  backup (I don't remember seeing it crash though).

Future plans:
-------------
- improve OpenGL rendering speed (text rendering seems to be taking the most
  time on my machine.)
- make Musagi not take 90% cpu time when idle (0% would be nice.)

Musagi on the Web:
------------------
- https://bitbucket.org/stqn/musagi-stqn
  You can get the source code and report bugs there.

- http://www.drpetter.se/project_musagi.html
  Original Musagi web site. Contains more info about Musagi and a nice tutorial.

- http://drpetter.proboards.com/index.cgi?board=musagi&action=display&thread=82
  "Open Source" thread on the official Musagi forum.

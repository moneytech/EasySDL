EasySDL lib 0.5.1
===========================

SDL lib, EasySDL permit to create program with SDL 1.2 easily.

Authors: 
- TAHRI Ahmed @Ousret
- SIMON Jérémy @Jokoast


What new in 0.5.1 ?
- Much faster than rev 0.4
- Less memory used
- Fix bug in SDL_unloadallSound()
- Rename few func (prefix mod become edit now) 

-------------------------------------
EasySDL 0.5
-------------------------------------

CMake is needed.
Install included.

`#include <ESDL.h>` to your project
- Then link with `-lsdl -lsdl_ttf -lsdl_image -lfmodex -lESDL`

Doxygen: http://spitajoke.com/tahri/EasySDL/doxygen/

-------------------------------------
LICENCES
-------------------------------------

SDL & SDL_ttf & SDL_image are under zlib licence.

fmodex licence: http://www.fmod.com/files/public/LICENSE.TXT (NO COMMERCIAL USE)

“FMOD Sound System, copyright © Firelight Technologies Pty, Ltd., 1994-2014.”
“Audio engine : FMOD Sound System by Firelight Technologies”
“FMOD by Firelight Technologies”

EasySDL is under GNU GPL v2.0

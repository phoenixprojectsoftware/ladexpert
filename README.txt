This Premade folder is almost all sit up but you have to do some things to
it.

First things first I recommend you to change the name of the folder mod to
something diffrerent so it does not interfer with any other mods. It does
not have to be anything to do with your mod or tittle. Like for a mod I am
makeing I have 2 version folders. So I can put them both in steam they can
not have the same name. So I named the testing one Pie and the one that is
stable and working OB short for Out-Break. Nameing your folder different will
not change the tittle in Steam.

This is not a drag and drop situation yet still need to do a few more things

First Open up the liblist.GAM file with notepad/wordpad/ETC

It will look like this

// Valve Game Info file
//  These are key/value pairs.  Certain mods will use different settings.
//
game "MODNAMEHERE"
startmap "STATMAPHERE"
trainmap "TRAININGMAP"
mpentity "info_player_deathmatch"
gamedll "dlls\hl.dll"
gamedll_linux "dlls/hl.so"
gamedll_osx "dlls/hl.dylib"
secure "1"
type "singleplayer_only"

Now change the Out-Break to What ever you want the name to be in Steam like
"PIE KILLS PEOPLE"
Still not done, change the start map to whatever map you made to start on.
So instead of "Begins" you should change it to "I_like_PIe"
If you have a Training map or a second story change the "Training" to the 
map name like "PIE_FOR_ALL"
Leave every thing else alone so it should look like this after this tutorial

// Valve Game Info file
//  These are key/value pairs.  Certain mods will use different settings.
//
game "PIE KILLS PEOPLE"
startmap "I_like_PIe"
trainmap "PIE_FOR_ALL"
mpentity "info_player_deathmatch"
gamedll "dlls\hl.dll"
gamedll_linux "dlls/hl.so"
gamedll_osx "dlls/hl.dylib"
secure "1"
type "singleplayer_only"

For a even simpler way here

// Valve Game Info file
//  These are key/value pairs.  Certain mods will use different settings.
//
game "Dumbass put tittle here"
startmap "Stupid put start map here"
trainmap "Please put training map here"
mpentity "info_player_deathmatch"
gamedll "dlls\hl.dll"
gamedll_linux "dlls/hl.so"
gamedll_osx "dlls/hl.dylib"
secure "1"
type "singleplayer_only"

Now put all your files where they need to go.

NOTE: DO NOT CHANGE dlls or cl_dlls UNLESS YOU HAVE YOUR OWN TO INSTALL

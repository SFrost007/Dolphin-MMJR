Discord = https://discord.gg/NZTQRpy5B3

### Fork Notes

This fork is a quick hack to add a new runtime button for GameCube emulation
which "replugs" the memorycardfolder. This works around issues in some games
(e.g. Wind Waker) where the memory card will be detected as corrupted after
using save states, and allows a regular save to be recovered.

1. Load the savestate
2. Tap the GameCube logo button on the toolbar
3. Use the regular in-game save functionality

Some games (again e.g. Wind Waker) may think that the memory card is "different"
than it was originally and still refuse to save. In this case delete the memory
card file from `Internal/Dolphin-MMJR/[region]/Card A/[game].gci` and repeat
steps 2-3 above.

This fork is also "rebranded" with an altered applicationId to allow it to be
installed side-by-side with the regular version of MMJR. This is not an attempt
to take anything away from MMJR itself and purely for convenience of having the
"real" version alongside this altered one. This will still save data into the
same `Internal/Dolphin-MMJR` folder, so can be used to recover save games from
states created in the main build.



### ANNOUNCEMENT (For new users):

=============================

I officially announce that I will be stopping any further development on BOTH projects and calling it quits to focus on University. Sorry to everyone that held in here for further development on |MMJR2| and for possible fixes down the line for |MMJR| .... but it really is too much for me to handle right now.

Both versions are on github and I encourage determined or curious people to use the source code. However at the rate that Dolphin Official is going, down the line you might not need |MMJR| or definitely not |MMJR2| anymore. I might have time to push any PR's over to Dolphin Official from |MMJR2| for QOL stuff like the theme changer or maybe the quick menu but like I said everything is on github and free to access so anyone can do it if in case I can't. 
As for whether I will come back and tackle this project again ... I have no clue;  I might still try to work on it little by little over time but as it stands I'm officially too tied down with IRL stuff to handle the projects anymore.

So special thanks to @Lynx  for his godly help and contributions and the testers; especially @Gamer 64  for his assistance over the recent months. As well as to @Jos  for the great updates, knowledge and development over at Dolphin Official (https://dolphin-emu.org/download/). Thanks to everyone for supporting the app, development and my endeavors in learning coding from scratch. 

=================================

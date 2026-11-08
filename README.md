# Blasterbug-steam---Switch-Pro-Button-Icon-Fix
Fixes the X/Y and B/A iconography when changing to Switch Pro Icons in the Graphics Menu (The original game's iconography only functions accurately if you're using Steam's 'Use Nintendo Button Layout' feature. Most controllers are automatically going to register as standard Xbox controllers when plugged in, even Nintendo 8bit-do controllers.)

In Blasterbugs, when changing the visual button iconography in the graphics settings, the X/Y and A/B buttons are not correctly assigned.
I edited the data.win file to swap X with Y and A with B.
Now, when changing the button icons to 'Switch Pro' the game shows:
- the 'Y' icon when referring to the Left face button
- the 'X' icon when referring to the Top face button
- the 'B' icon when referring to the Bottom face button
- the 'A' icon when referring to the Right face button

Originally, the Nintendo iconography is only accurate when strictly using Steam's 'Use Nintendo Button Layout' fucntionality, 
within a controller's advanced settings.

It seems most natural to me that someone looking to change the iconography may not strictly be using a Nintendo Pro controller.
They may be simply be plugging in an 8bit-do controller (which might be automatically identified as a standard PC controller.
Or, they may be using an Xbox or Playstation controller, but simply wish to see the Nintendo icons associated with the expected positional buttons.


This mod consists of a replacement 'data.win' file, with the icononography corrected.
To install, right click on the game in your steam library and click on 'Browse Local Files'.
Replace the unmodded data.win file that's in this folder with the modded data.win file from this project page.
(I highly recommend backing up the original data.win file, though reinstalling the game would restore it just the same)

That's it.
All button icons should now be accurate to their expected positions, regardless of what controller you're using.
(Unless you're using an actual Nintendo Pro controller, which may automatically be recognized as such in Steam,
and will automatically set the Nintendo Button Swap functionality in Steam's Advanced Controller settings.)

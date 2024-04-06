# SME-Assignment

Documentation

## Task 1

I integrated the SFML Headers and library as per the provided instructions. This involved copying the header and lib folders from the SFML zip and pasting them into the sfml folder.  then i tried to run .sln file in Visual Studio, it took approximately 10 minutes.

## Task 2

The errors were located in the PlayerController.h file, consisting of:
- Syntax error: missing ';' before '*'
- Unexpected token(s) preceding ';'

Despite thorough examination, I couldn't pinpoint the exact cause of the error. Although initially suspected within PlayerController.h, all seemed fine within the file 

The 'unexpected token(s) preceding ';'' error suggests the compiler's inability to recognize PlayerView and PlayerModel as valid types during pointer declaration. However, both classes are properly defined in source/Player. 

Additionally, I noticed the absence of my .exe file while adding bin files to x64/debug, which might have hindered local project setup.
 this took me approximately 3 hours.

## Task 3

To enable firing of the player ship:
- Uncommented the firing implementation in processPlayerInput() within PlayerController.cpp.
- Implemented fireFrostBeam() method in SubzeroController.cpp for Subzero to fire FrostBeam.
- Implemented fireTorpedoes function in ThunderSnakeController for heavy damage bullets.
- Implemented fireLockedMissiles() in zapperController.cpp for locked-on missiles targeting the player.

Time taken: Approximately 45 minutes.

# SME-Solution

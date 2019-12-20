# winterWonderland
Calm winter-based game in which you play as an elf who interacts with his environment!

This game is still in development! Early early earrrrly version being released just to keep track of what is being done between versions.
So, what has been done so far:

Player: moves around a world (WASD) and interacts with objects (clicking). You can switch between unlocked skins (right arrow button)
which you obtain by completing unknown achievements! Finally, there is a save feature (V) that saves your progress and statistics to a file.

Objects \ entities: Collision is detected on the top and bottom sides of each object, and layering is complete so that when the player is above
an object it shows the object in front of the player. Each object, when hovered over with the mouse, shows an outline that confirms it's
selected. When an object is clicked on, a random phrase will pop up from that object (some are worse than others, you've been warned!).
Entities created so far: trees and penguins.

Weather: snow, just for asthetic reasons, doesn't change anything in-game except make it feel more like winter!

Hopes for the future:

- create a panel that shows controls
- create a panel that shows statistics (steps taken, number of interactions, etc.)
- create deer \ reindeer, polar bears, and other but much rarer entities!
- add more skins (only 8 as of now, 1 permeanently unlocked as the starting skin and 7 able to be unlocked)
- music (being worked on!)

NOTE: When you download the .zip file, extract it in a folder, because the .jar file needs the images+and+data folder in order to put the
images on screen and also to read in your skin and statistics data. Over all else just make sure they're in the same place, whether it be on your desktop or in a folder.




VERSION UPDATE NOTES:




Version 2:

+ Added goblins! Sit still until you get close enough, then they chase after you!
+ Made skin selecting easier, now you can use both the left and right arrow keys to switch between skins not just
the right arrow key
+ Added an autosave feature (15 min intervals)
+ Added 4 more skins to be unlocked!
+ Implemented random replacement! -
    This means that whenever an object has been interacted with, and you go far enough away from it, it will
    be replaced with another random object, making it so the environment is always changing.
+ Fixed a bug with interacting - before, you could endlessly click on an object and rack up your number of
interactions, now this has been fixed so that as long as an object's phrase is present, it can't be interacted with.
+ Made interacting easier. Before, if you were going to interact with something, you'd most likely have to sit still
and click on it, but now you can continue running and click on whatever you desire!

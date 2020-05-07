# Locomote_proto

**06.04.2020**

Tried with physics by tiles being child actor there was problem. 

So using simple transform change in Z axis and destroy,

It does add "dynamism" and "feedback to movement".

//OOP is incredible! Had to do change in base and all tiles got the ability.


**02.04.2020**

&#43; XP for each level is awarded only on first win.

&#43; Main Menu - Level Button are now WB 

&#43; Main Menu  - Level buttons Show win/loose

&#43; Decreased Swipe Speed

&#43; Added "Key". Award on XP milestones. Buy. Use "Add Turns" in HUD

&#43; Fixed double HUD

&#43; Fixed "Dark Mode" in mobile! From Constructor to BeginPlay


**01.04.2020**

&#43; Settings (Reset Data, Zoom threshold)

&#43; Two finger distance output

&#43; "Reset" now also resets the camera

&#43; "Pinch" to control Zoom (Z) //Broke my brain

&#43; "Dark Mode" in Settings, affects Sky Sphere. //For your 4:00 am test

&#45; DM toggle not working on my phone (does on computer)

**01.04.2020**

&#43; "Restart" on "Turn Over" works.

&#43; Added directional Tiles (angle not working)

&#45; Don't worry about 0 XP, not matters right now.

**31.03.2020**

&#43; Increased camera pitch by 10 degrees.

&#43; Added "Restart" level button in HUD.

&#43; Before "Win"/"Loose" UI, HUD is removed.

&#43;  XP Earned" in "Win" UI

&#43;  Moved "Make Coll Array" to Contractor from BeginPlay. //crashes fixed?

&#43; Rudimentary scroll wheel to camera X-axis

&#45; Retry not set to work in "Loose"

**29.03.2020**

&#43; "Finish" tile activation/deactivation feedback

&#43;  Fixed win/loose condition

&#43;  Clicking current tile now won't decrement turn.

&#43;  Moved lots of code from Pawn to Controller. General refactoring.

&#45; Rotation locked in yaw only for now

&#45; Removed maps with "2" size tiles //maybe the casue of crash. But it still does.

**28.03.2020**

&#43;  Added two (thinner and bordered) tile types.

&#43;  Tile 2 skip added (Now using moved collision boxed, instead of rellay)

&#43;  Negative turn fixed

&#43;  Pan Y asix flipped.

**27.03.2020**

&#43;  Added Tile Base, and planted all fucntions to it.

&#43;  Increased zoom scale

&#43;  Added tile activation propagation count.

&#43;  Win UI pops only after pawn properly moves to tile.

&#43;  Added diagonal tile sensing.

&#43;  Added Walked Tile neighbor deactivation.

&#43;  Added level of diagonal type

&#45; In level 3 tap on the starting tile to begin (it is a bug only in mobile)


Developed with Unreal Engine 4

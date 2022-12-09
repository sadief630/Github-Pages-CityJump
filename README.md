# Github-Pages-CityJump
 Game Project from CSC 2463

A motorcyclist doing stunt jumps and driving through city streets (a run/jump/stop game). It's kind of like the Google Dino Jump Game! The objective of the game is to survive as long as possible without failing a quicktime event, which consists of time-sensitive obstacles and red lights that the player must succeed at avoiding to continue the run. The game will end after the biker “crashes” by missing a quicktime event. There is a score ticker that tracks progress, as well as a timer that tracks the distance elapsed. The  final score will be dependent on the amount of obstacles jumped. The game will get more difficult as time progresses, indicated by score thresholds.

There are three different game states:
Start Screen, with Character Selection
Game run
Game over/Restart Screen, which displays your score

Graphics Elements: 
The obstacles and the main motorcyclist(s) will be sprites with different respective animations. I will create a class for the character sprites, the different obstacle sprites (fire hydrants, trash cans, or traffic cones), and code specifically to their appropriate animations/actions. The biker will have to jump depending on the quicktime event. They will all be a pixel-art style and created by me in GIMP.

Sound Elements: 
There are more than 3 Tone synthesizers that construct the game music - several for each game state. I use loops and parts, as well as different filters and effects depending on what I feel the game’s soundtrack should sound and feel like. I made a synth also to replicate the revving of the motorcycle when the player jumps with Distortion and Vibrato effects. I also have very short (<= 3 second) audio clips for sounds such as the selection, light changes, button presses, and the motorcycle crashing if a quicktime event is failed. 

Gameplay Elements: 
The first quicktime event will be jumping at the correct time to avoid obstacles. You can press any key (except ENTER) to jump over trash cans, traffic cones, and fire hydrants. The second quicktime event, stopping, will use on-screen lights and the ENTER key: whenever a yellow LED light turns on, the user will have a short amount of time to prepare to press the button promptly. The user must press the ENTER button WHILE the light is red. Shortly after, the motorcycle will crash if the user has not pressed the button before the light turns green again.

Other important information: 
The sprite sheets, backgrounds, and other objects are all drawn using GIMP software or built-in p5 draw and shape functions. All sounds that are not p5 compositions are sourced from freesound.org. 

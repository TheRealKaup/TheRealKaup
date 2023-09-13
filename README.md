# Hello. I am Kaup, the developer of KTech.

## KTech is my C++ terminal game engine. It is like any other basic 2D game engine, but its graphics are terminal based.

### _In today's world, it is common for new games to release after most of their development resources were invested into their graphics, instead of their game experiences themselves. This phenomenon usually causes affected games to be not as good as expected by the players, leading to disappointment among the fan base. KTech solves this issue by implementing old and primitive graphics that are easy to use, look fine and can't become a huge and complex process in the development._

### KTech is currently capable of:

- Rendering with layers, opacity, 24 bit color range
- Processing collision with event handling, collider types, pushing, blocking...
- Loading, mixing and playing sound
- UI such as input fields and buttons
- Handling time and managing invocations
- Handling input
- Some other quirks and features

### At the time of writing (September of 2023), KTech and its interrelated projects are still private. I hoped to release things by the end of August, but that didn't happen. This is what I have left to do before releasing KTech:
- Develop "NETSET" (a game I am making with KTech) and bring it to a presentable pilot state.
- Finish writing KTech's documentation and tutorials, including tutorials in video format.
- Make some minor improvements and changes to the engine.

### Some intereseting information about KTech:

- KTech is simply a library, but I made an application (using KTech itself) called "TextureCreator" which helps creating terminal-graphics textures, and perhaps in the future more applications similar to this will be created, and a proper software development kit will come to be. 
- The game developer (the KTech user) constructs their own game loop with functions that the engine comes with.
- Although KTech's level is quite low, It tries to be easy to use, and friendly for new game developers.
- The engine relies only on the CPU for its processing (audio, rendering, collision...) and achieves more than playable performance.
- Making a game with KTech can be done entirely from a terminal by using a terminal text editor (like Vim) for writing code, the TextureCreator application for creating textures, a C++ compiler accessible from a terminal to create an executable, and by simply running the game and playing it in the terminal.
- I started developing KTech in March 2022. I had many breaks, sometimes as long as a month. Whatsoever, this is still, the biggest programming project I have ever had, and I wouldn't be surprised to know that until now I have spent a 4 digit number of hours working on it.

### This is how a very simple game made with KTech can look like:
![KTech Small Game](ktechsmallgame.png)

### Other projects interrelated with KTech:

#### TextureCreator
An application made with KTech for creating KTech texture files. This program is needed for creating KTech textures because each terminal character cell has an RGB foreground, RGB background and a character values. This kind of texture can't be created by a normal pixel-based image creator.

![TextureCreator Screenshot](texturecreatorscreenshot.png)

#### ThatGame
A game made with KTech that I am working on alongside KTech itself. In the game the player plays as a freelance hacker that gets hacking jobs from the darknet. The game is called "ThatGame" because, weeks into development, I still don't have a name for it, and I use this name to refer to it. The game involves a networking simulation sandbox kind of thing, and the player follows a story line rather then getting randomly generated jobs from clients.

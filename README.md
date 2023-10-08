# Hello. I am Kaup, the developer of KTech.

## KTech is my C++ terminal game engine. It is like any other basic 2D game engine, but its graphics are terminal based.

### _In today's world, it is common for new games to release after most of their development resources were invested into their graphics, instead of their game experiences themselves. This phenomenon causes the affected games to lose quality, leading to disappointment among the players. KTech solves this issue by implementing old and primitive graphics that are easy to use, look fine and can't become a huge and complex process in development._

### KTech is currently capable of:

- Rendering with layers, opacity, 24 bit color range
- Processing collision with event handling, collider types, pushing, blocking...
- Loading, mixing and playing audio
- UI such as input fields and buttons
- Managing time and invocations
- Handling input
- Some other quirks and features

### At the time of writing (September of 2023), KTech and its interrelated projects are still private. I hoped to release things by the end of August, but that couldn't happen.
I can release KTech only after I:

- Make some minor improvements and changes to the engine.

And preferably, also:

- Finish writing KTech's documentation and tutorials, including tutorials in video format.

But, I currently prefer working on:

- Develop "netset" (a game I am making with KTech) and bring it to a presentable pilot state.

### Some intereseting details about KTech:

- KTech is simply a library, but I made an application (using KTech itself) called "TextureCreator" which helps creating terminal-graphics textures, and perhaps in the future more applications similar to this will be created, and a proper software development kit will come to be. 
- The game developer (the KTech user) constructs their own game loop with functions that the engine comes with.
- Although KTech's level is quite low, it attempts at being easy to use, friendly and intuitive for new game developers.
- The engine relies only on the CPU for its processing (audio, graphics, collision...) and achieves more than playable performance.
- Making a game with KTech can be done entirely from a terminal by using a terminal text editor (like Vim) for writing code, the TextureCreator application for creating textures, a C++ compiler accessible from a terminal to create an executable, and by simply running the game to play it in the terminal.
- I, Kaup, started developing KTech in March 2022. I had many breaks, sometimes as long as a month. This is the biggest programming project I have ever had, and I wouldn't be surprised to know that until now I have invested a 4 digit number of hours into developing it.

### This is how a very simple game made with KTech can look like:
![KTech Small Game](ktechsmallgame.png)

### Other projects interrelated with KTech:

#### TextureCreator
An application made with KTech for creating KTech texture files. This program is needed for creating KTech textures because each terminal character cell has an RGB foreground, RGB background and a character values. This kind of texture can't be created by a normal pixel-based image creator.

![TextureCreator Screenshot](texturecreatorscreenshot.png)

#### netset
A KTech game in active development. In the game the player is a freelance hacker that gets jobs from the darknet. The game involves a networking simulation, and the player follows a story line rather then receiving randomly generated jobs. The gameplay consists of searching for information, analyzing it and converting it into new information, until the goal is reached.

Here's a screenshot of the game, from 9.10.2023 (d/m/y):

![netset screenshot from 9.10.2023](netset-9.10.2023.png)

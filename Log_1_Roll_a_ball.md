# Roll-a-ball

We completed the roll-a-ball guide and learned the basics of creating games in Unity.

The game is a very simple implementation of a ball rolling around and picking up objects.
Picking up an object will increase a number on the screen, which is the "score" of the game.
After having picked up all the game objects in the game arena, the game will end and display a victory screen of sorts.
The arena is a basic square with walls preventing the ball from going out of bounds. That was the theory atleast, however in practice, the ball
is actually able to scale the walls and leave the gameplay area.
The ball is able to roll in any direction and can be controlled with both WASD and the arrows.


In the development process there were some minor issues. These issues were mainly related to the choice of the IDE. We have solely used Rider as an IDE for C# up until this point, however working with Unity that proved difficult. 
Rider kept complaining about the scripts and in the end it was far more feasible to switch to Visual Studio.

Continuing in the issue department, as a new user of unity there were some mishaps here and there, which made Roll-a-ball confusing. In the early stages we accidentally meddle with the camera and the view and had no idea how to reset it. In the Unity Editor this part is not very intuitive for a new user but this was also, in the end, a good learning experience in handling the editor.

Here are some screenshots of the game:

![image](https://github.com/Esben-Andreas-Madsen/GMD1/assets/91538845/5030d6bb-6c5e-42d5-9be3-b34dbbba4092)

![image](https://github.com/Esben-Andreas-Madsen/GMD1/assets/91538845/94bceab7-ced2-4bfd-a2bc-18bef1299392)

![image](https://github.com/Esben-Andreas-Madsen/GMD1/assets/91538845/2b232f60-6871-423b-915e-68ccf749c222)

The game was deployed on github-pages but shows the following:

![image](https://github.com/Esben-Andreas-Madsen/GMD1-Roll-a-ball/assets/91538845/9cc5d2fa-4503-4f1b-8c6c-65618d3ba632)

~~Haven't found a solution to this yet. :(~~

Building with Decompression fallback solved it.

# Student Work
Though it's been quite a while since I was at the University of Texas at Austin, I thought it worth archiving my thoughts on the projects I did there.

* [Hangtime](#hangtime)
* [Faiurbulz and Swaurdz](#faiurbulz-and-swaurdz)
* [After](#after)

### Hangtime
#### (Jan 2015 - May 2015), Team Movement - Windows, Mac, Linux
![Hangtime action shot](/images/HangtimeAction.png "The player character swings from one of the grapple nodes.")

Hangtime was my team's 3D Game Development Capstone project, done in Unity 4.6.  I was primarily responsible for gameplay and shader programming.  Though I did not serve as the designer on the team, the original idea for a game about swinging from a grapple device was mine.  As gameplay programmer, I developed the swinging mechanic, first experimenting with a PhysX-based solution, then transitioning to a completely script-driven one.  I could probably write multiple paragraphs on why the physics joints didn't work.  While the shader that defined the look of our game was not written by me, I ended up taking on its maintenance and developing more shaders based on it, such as the water and lava shaders, which define the sinusoidal movement of the surfaces to which they're attached.

As for the game itself, Hangtime is an over-the-shoulder 3D platformer based almost entirely around the swinging mechanic.  The design philosophy we've had from the beginning is that if the player is on the ground, or motionless, for any appreciable amount of time, we've done something wrong.

[See the trailer for Hangtime here.](https://www.youtube.com/watch?v=MDBuhvkByjM)

### Faiurbulz and Swaurdz
#### (Apr 2015 - May 2015), Fab101 - Linux
Faiurbulz and Swaurdz was my team's Game Technology final project, developed on a custom engine that employs Ogre3D, Bullet, SDL Audio, and CEGUI.  For the engine, my focus was on Bullet integration and construction of the Unity-like component-based system we use for objects in the game.  For the game itself, I took the lead on the gameplay, as I also served as lead designer on the project.

F&S is a goofy top-down omni-directional shooter that also employs melee combat.  The player plays as a spellblade (a person who fights with magic and melee weapons) as they fend off hordes of knights and wizards, who are offended by your combination of their arts.

### After
#### (Aug - Dec 2015), Transient Games - Windows, Mac (Web)
![After gameplay shot](/images/AfterAction.png "The player character climbs down a ladder to explore the environment.")

After was my team's 2D Game Development Capstone project, done in Unity 4.5.  I was responsible for gameplay programming, which involved tuning player character movement and creating the ladder, rope swing, and object-pushing systems.  I also contributed to the overall design of the game, which was a task shared by the whole team.

After is a sidescrolling puzzle/adventure game with an emphasis on narrative.

If you'd like to play it, you can find [After on the UT Austin GAMMA site](http://www.cs.utexas.edu/~gamedev/fall-2014/Transient-Games/Release.html).  It is a web build, so the [Unity Web Player](http://unity3d.com/webplayer) is required (sorry, Linux-users!).  You can also find the [trailer on Vimeo](https://vimeo.com/113364865).
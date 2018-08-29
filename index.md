## What I'm About  
I've been playing video games as my primary hobby since I was in first grade, and I was around computers longer than I can remember.  While I started out mostly playing games on consoles like the Nintendo 64 and Nintendo GameCube, I've moved over to PC gaming almost exclusively, with a small exception for various Nintendo games.  While I'm not the hardest of hardcore (never booted up Dwarf Fortress or EVE Online, for example), I am passionate about the artform and the industry.  I've been working on games professionally since the summer of 2015, and have had a wonderful career thus far.

## Important Links

[LinkedIn profile](http://linkedin.com/in/pixley)

## My Projects

### Unannounced Project (Sept 2017 - Present), Hi-Rez Studios

I currently work for Hi-Rez Studios as a Software Engineer on an unannounced project.  I am unable to provide any details at present.

### Realm Royale (Jun 2018 - Aug 2018), Hi-Rez Studios

![Realm Royale Logo](https://web2.hirez.com/realm-royale/assets/realm-royale-logo.png)

Realm Royale is a fantasy third-person battle royale, loosely based on Paladins.  Starting life as a game mode within Paladins, Realm Royale runs on Unreal Engine 3.  My team was briefly brought on to assist the Realm Royale team as the game exploded in popularity.

During the handful of weeks I worked on the project, my major responsibilities were adding new gameplay systems and improving console gameplay feel.  As part of this effort, I built or helped to build:

* An entirely new class, complete with new abilities, a passive, and a weapon.
* A 50 vs 50 royale-style game mode.
* A completely reworked aim assist system from that inherited from Paladins' codebase.
* Fixes for various console certification failures around network connectivity loss.

### Hand of the Gods: Smite Tactics (May 2017 - Sept 2017), Hi-Rez Studios - Windows, Xbox One, PlayStation 4
![HotG key art](https://web2.hirez.com/smite-tactics//wp-content/uploads/2018/02/HotGNoLogoBlog-848x477.png)

Hand of the Gods is a spin-off of the popular MOBA Smite, combining the casual fun of collectable card games with the mind-games of turn-based tactics, tied together with Smite's colorful cast of deities from around the world.  It's been described as a hybrid between Hearthstone and modern XCOM, which is not an unfair comparison, in my opinion.  Like its parent game, HotG is free-to-play.

Hand of the Gods was built in Unreal Engine 4 over the course of about a year and a half.  I joined the project as a gameplay programmer, but I quickly moved over to UI work, as my previous experience with Unreal Motion Graphics was vital to the project.  As part of the effort to replace the old Coherent-based UI with a new UMG-based one, I was responsible, in part or in whole, for the following client-side features over the months I was on the project:

* Friends and Clans - interfacing with Hi-Rez backend and widget programming
* Settings menu - widget programming
* Chat system - interfacing with Hi-Rez backend and widget programming
* Front-end tutorial (explaining the out-of-game loop)
* Gamepad support
* Quest Log and Player Statistics - interfacing with Hi-Rez backend and widget programming
* Player Ranking - interfacing with Hi-Rez backend and widget programming
* In-game store - interfacing with Hi-Rez backend and widget programming
* Cosmetic customization - interfacing with Hi-Rez backend and widget programming
* Deck selection and display
* Display and navigation of cards within the player's hand
* Generalization of C++ supporting code for use in other Hi-Rez UE4 games (gamepad support, widget organization and focus, interpreting data from the Hi-Rez framework into Blueprintable classes and structs)

I learned a lot about Unreal Engine working on HotG, especially regarding UI.  Even though I knew a lot about UMG, I learned so much more about how to manage and navigate widgets.  Descent: Underground's UI was severely hampered by having to exist solely within the confines of Blueprint, because there was so much to be gained by putting the widget management on a C++ backbone.

Hand of the Gods: Smite Tactics was fully released in February 2018 and is available on Steam, PlayStation Store, Xbox Store, and on the [Hand of the Gods website](https://www.handofthegods.com).

### Descent: Underground (Jun 2015 - Apr 2017), Descendent Studios - Windows, Mac, Linux
![A player's Torch and a hostile AI Predator face off within the Charon facility](http://i.imgur.com/acjoKmT.png)

Descent: Underground is a first person shooter where players control drones within asteroids to fight over limited resources needed by a dying Earth taken over by gigacorporations.  Battles are fought in all six degrees of freedom as drones stay alive by dodging incoming projectiles.

It was my first professional project. It is being built in Unreal Engine 4.  I was a gameplay programmer on the project, responsible for drawing up design for and implementing such systems as the following:

* Environmental interaction
* Matchmaking web API communication
* Weapons and other combat systems
* UI design and integration
* Game mode and related asset implementation
* Chat system frontend design and integration
* VR gameplay elements
* Power-up management
* Player option configuration
* Client-server communication

DU's game code is interesting in that it is done almost entirely in Blueprint, allowing extremely rapid iteration, which we felt was especially necessary for such a small team on a crowdfunded budget.  Looking back, however, there were some serious limitations that could have been overcome by moving the codebase to C++ early in development.

In addition, I was also responsible for supporting the game as a live product, providing minor game design as part of team-wide discussions, supporting design and art integration, and community interaction as part of our open development.

Descent: Underground is available on Steam and on the [Descendent Studios website](https://descendentstudios.com).

[See gameplay from before I left the project here.](https://www.youtube.com/watch?v=MiGZi3fufEA)

### Hangtime (Jan 2015 - May 2015), Team Movement - Windows, Mac, Linux
![The player character swings from one of the grapple nodes](https://i.imgur.com/3Bii8gn.png)

Hangtime was my team's 3D Game Development Capstone project, done in Unity 4.6.  I was primarily responsible for gameplay and shader programming.  Though I did not serve as the designer on the team, the original idea for a game about swinging from a grapple device was mine.  As gameplay programmer, I developed the swinging mechanic, first experimenting with a PhysX-based solution, then transitioning to a completely script-driven one.  I could probably write multiple paragraphs on why the physics joints didn't work.  While the shader that defined the look of our game was not written by me, I ended up taking on its maintenance and developing more shaders based on it, such as the water and lava shaders, which define the sinusoidal movement of the surfaces to which they're attached.

As for the game itself, Hangtime is an over-the-shoulder 3D platformer based almost entirely around the swinging mechanic.  The design philosophy we've had from the beginning is that if the player is on the ground, or motionless, for any appreciable amount of time, we've done something wrong.

[See the trailer for Hangtime here.](https://www.youtube.com/watch?v=MDBuhvkByjM)

### Faiurbulz and Swaurdz (Apr 2015 - May 2015), Fab101 - Linux
Faiurbulz and Swaurdz was my team's Game Technology final project, developed on a custom engine that employs Ogre3D, Bullet, SDL Audio, and CEGUI.  For the engine, my focus was on Bullet integration and construction of the Unity-like component-based system we use for objects in the game.  For the game itself, I took the lead on the gameplay, as I also served as lead designer on the project.

F&S is a goofy top-down omni-directional shooter that also employs melee combat.  The player plays as a spellblade (a person who fights with magic and melee weapons) as they fend off hordes of knights and wizards, who are offended by your combination of their arts.

### After (Aug - Dec 2015), Transient Games - Windows, Mac (Web)
![The player character climbs down a ladder to explore the environment.](http://i.imgur.com/B6Y5RyE.png)

After was my team's 2D Game Development Capstone project, done in Unity 4.5.  I was responsible for gameplay programming, which involved tuning player character movement and creating the ladder, rope swing, and object-pushing systems.  I also contributed to the overall design of the game, which was a task shared by the whole team.

After is a sidescrolling puzzle/adventure game with an emphasis on narrative.

If you'd like to play it, you can find [After on the UT Austin GAMMA site](http://www.cs.utexas.edu/~gamedev/fall-2014/Transient-Games/Release.html).  It is a web build, so the [Unity Web Player](http://unity3d.com/webplayer) is required (sorry, Linux-users!).  You can also find the [trailer on Vimeo](https://vimeo.com/113364865).

## Technical Experience  

### Unreal Engine 4

UE4 is what I've worked within for my entire career up to this point.  It's my favorite engine I've worked with thus far.  Both Blueprint and Unreal's spin on C++ are very familiar to me, having done gameplay and UI programming in both.  UE4 provides very powerful tools that make all sorts of games possible.  I've worked on a 6DoF shooter and a card game in UE4, and it works excellently in both cases.  I can understand why so many games are hopping on the UE4 wagon, from fighting games like SoulCalibur 6 to RPGs like the Final Fantasy VII remake to massive-scale shooters like Fortnite and PlayerUnknown's Battlegrounds.

### Unity 4

Most of my student projects were in Unity, but I haven't used it since.  That doesn't mean I don't have good things to say about it.  I think it has UE4 beat in terms of pure 2D games, given Unreal's languishing Paper2D plugin.  It worked great for me in college, and there are plenty of great games that make incredible use of it, such as Guns of Icarus Online and Superhot.

## My Favorite Games  
I hold the belief that, if one wants to create games, he/she must understand what makes for good games.

Quick note: Unless stated otherwise, I think the soundtrack to any game on this list is good enough to have on my primary playlist.

### Mass Effect 2 and 3  
The exclusion of ME1 in this heading is not to say it's a bad game, because it's a great game, but there are things that set 2 and 3 apart that make them two of my favorite games of all time.  To me, those games truly understand what RPG means.  As a tabletop gamer, RP means a lot more to me than stats.  It's about choosing how the character interacts with others, how the character carries itself, and what abilities the character has and uses.  All three Mass Effect games have this in spades, and it can certainly be argued that the first game was the best in that regard (though that is not an argument on which I have a strong opinion either way).  What 2 and 3 nail, though, is that they have that and the engrossing setting, but also the gameplay is rock-solid.  Sure, 2 and 3 play like most other cover-based third-person shooters, plus the ability usage, but it is polished, especially in 3's case, and, unlike most cover-shooters, the unlockable abilities, the different character classes, and the different squad compositions keep thing fresh.  Because of that, I have never not finished a playthrough of either ME2 or ME3.

### Metroid Prime  
Metroid Prime is the first game I can remember definitively saying that it was my favorite.  I'm not about to heap praise on it for flawlessly bringing Metroid to the third dimension, because it was the first Metroid game I ever played.  What engaged me so effectively the first time I played it was the gameplay and how varied it became as the game went on.  I would often get an item and realize that I could use it in a place I had visited before to unlock a new area, and it became obsessive for me to get to the next ability.  While that's still fun, as I've grown older (because I first played it when I was twelve), I've come to appreciate it more.  The game has so much backstory to discover through scanning murals, terminals, and enemies, and that's not something I did the first time.  Going back as an adult, though, I find myself pouring through the journal logs, discovering what the Phazon meteor did to the Chozo on Tallon IV and what the Space Pirates have been doing with Phazon and Metroids.  It's this mystery to uncover as the game progresses, and I love it.  Also, Samus Aran is a boss.  She just is.

### XCOM 2  
While I haven't really gotten into tactics games, Firaxis's take on XCOM has gotten hundreds of hours out of me.  I love Enemy Unknown and Enemy Within, and XCOM 2 takes what they did and makes them even better.  The emergent character stories are made even better when the player is able to pre-populate the soldier pool.  Gameplay is given so much more variety when maps are procedurally generated instead of being the same 30-odd maps.  Stealth adds another layer to the tactics EU/W did so well.  A full-featured mod kit gives the game limitless potential, which is a welcome addition, given how much effort went into creating mods for EU/W.  XCOM 2's expansion War of the Chosen also adds more to the experience, with a system that draws from Shadow of Mordor's Nemesis System.

### Portal 2  
The original Portal was a great game.  It's fun, challenging, and witty.  Portal 2 took everything that made Portal 1 great and did it even better.  More puzzles, more hilarious characters (more in both quality and extent) taunting you over the PA, more world-building, more physics-bending mechanics, and more players.  The first time I played it, I did it in one sitting.  It was just that good, well, and it's short enough to do that.  A lot of games try to be funny, and it can come across as trying too hard, or it could go the "LOL SO RANDOM" route, but Portal 2 hits the mark.  It is one of two games I've ever had to pause to laugh at something it did intentionally.  JK Simmons, Stephen Merchant, and Ellen McLain all hit their performances out of the park.

### Far Cry: Blood Dragon  
This is the other game I've ever needed to stop to laugh at.  Even though I never really got into the mainline Far Cry games, I adore Blood Dragon.  I can tell that the devs really poured their hearts into that game.  The 80s references, the over-the-top weapons, and the fantastically funny dialogue all make for a very fun experience.  Of course, someone who hasn't seen a lot of cheesy 80s action movies probably wouldn't appreciate it, but it is an example of one of my favorite philosophies about creating art: the *right* people will get it.  Joel Hodgson was right when he said that about obscure references in Mystery Science Theater 3000, and I very much believe the same of Blood Dragon.  The game is just pure fun, and I can dig it.  It's one of four games I've ever 100-percented.

### Redout
Though it is an indie game among triple-A entries on this list, I have a deep appreciation for Redout.  Racing games generally go for a realistic style, but Redout eschews that for an abstract, polygonal aesthetic, giving it a ton of personality, and it suits Redout's futuristic setting.  The anti-grav racing giants Wipeout and F-Zero are a little before my time, but Redout has demonstrated why the sub-genre has such a cult following.  The sense of scale and speed oozes from this game, especially in VR.  As a racing game, Redout has the benefit of being able to work excellently on a flat screen and in VR.  Redout is one of those games that is easy to get into but allows the player a ton of mechanical mastery, and its career mode does an excellent job helping a player along that curve.  Also, I know I put the bit at the top of this section about soundtracks, but Redout absolutely deserves special mention.  Few games can consistently instill their soundtracks with their theme as well as Redout.  Every single track is filled with the urge to blast down the track at 1500 kph.  Seriously, listen to [On My Own](https://www.youtube.com/watch?v=2gE9Id2fSx0), which plays for races in the Alaska setting.

### The Legend of Zelda: Breath of the Wild
I generally have an overall negative attitude toward open-world games.  They're often sparse and shallow in content.  Breath of the Wild addresses these issues and runs with its own ideas.  It takes a lot to make a systems-driven game work, and BotW makes it look easy.  The puzzles make excellent use of the open-ended gameplay systems.  In many games, including previous Zeldas, puzzles introduce a mechanic, use it for a bit, and then it's never seen again.  BotW's puzzles take the opportunity to present existing mechanics in a completely new context.  The best part of it is that the player can then take those ideas and apply them in combat in the overworld.  It's like the logical conclusion of what Half-Life 2 did with the Gravity Gun.  BotW also makes use of the motion-assisted aiming that Splatoon introduced, which is a welcome advancement from the Wiimote-based aiming in Twilight Princess and Skyward Sword.  Visually, the game is breathtaking, if a bit held back by resolution and framerate.

## Games That Don't Quite Hit the Mark  
In addition to knowing what makes games great, I also believe it is important to consider what holds some games back.  Games on this list are great but flawed.

### Mass Effect 1  
There are a few reasons why I hold Mass Effect's sequels higher than the original game.  The biggest one is the combat gameplay.  Whereas in the other two games, where the player pushes a button to enter and exit cover, ME1 uses a sticky-cover system, which is often finicky.  I much prefer being able to make the decision myself as to when I crouch behind cover, and, luckily, this was recognized and rectified for the sequels.  One other thing that drives me nuts in ME1 is how autosaves can be in the dumbest places.  For example, the end of the mission in which you recruit Liara on Therum has the party get onto an elevator, have a conversation, ride the elevator for 30 seconds, watch a krogan and his merry band of geth walk out, have a conversation with the krogan, and then combat ensues.  Sure.  Fine.  But, that particular fight can be somewhat challenging, so the player will likely die on the first try.  The last possible save (because one can't save manually during combat, cutscenes, conversations, or elevator rides) is the autosave before the conversation at the bottom of the elevator, which means that all that has to happen again, which means, even with skipping every line of dialogue, it'll be about 2 minutes before the combat starts again.

### Middle-Earth: Shadow of Mordor  
It has a quick-time event instead of a final boss fight.  I was thoroughly enjoying the game until button prompts appeared on my screen to "fight" the final boss.  Three explicitly prompted button presses to win the game.  That is a foul to me.  As a person who enjoys thinking about game mechanics and their implementation, I consider QTEs to be the laziest form of mechanics design.  And this is in a game that has such a good combat system!  If the game had gone to its final cutscene after the huge fight against my nemesis, I would have been very happy.  Even the fight after the nemesis fight was creative and would have been a good note on which to end.  Let's put it this way: people were upset over the ending to Mass Effect 3.  I personally didn't mind that, but I was angry at the ending to Shadow of Mordor.  At least ME3's ending was centered around the most engaging part of the game (conversations).

### Geometry Wars 3: Dimensions
Geometry Wars 2 was one of my favorite games on the Xbox 360.  Dimensions is definitely a worthy successor, and it expands on the gameplay ideas of its predecessors in fun and engaging ways.  However, the game has lost a bit of the atmosphere.  This largely comes down to the music.  The Evolved themes from the first two games are two of my favorite tracks of all time (2's version being an excellent remix), with a blood-pumping beat and an appropriately retro sound.  Dimensions' Evolved theme, on the other hand, I find lacking.  It almost sounds like it's trying to get kind of close to the original theme, but different enough to not draw a lawsuit, and it's worse for it.  Now, I don't know the legal status of the soundtracks for the old Geometry Wars soundtracks, so that could very well be the exact case, but, even so, the new theme just doesn't quite get me into the same zone.  It just doesn't lend itself as well to blasting on max volume while blowing up glowing shapes.  To a lesser extent, this also applies to visual presentation, especially the UI.  The original games did an excellent job of presenting Geometry Wars as this "evolved" (heh) version of old arcade games.  Dimensions has largely ditched that mentality, which is a shame.  I love GW3, but I hate to see it held back from being as stylized and exciting as the older titles.

## Disappointing Games
There are some games that have an interesting premise and ideas, but are flawed in their execution.  These are a valuable case study into game design and how to limit scope.

### Mass Effect: Andromeda
I'm not going to lie here: I installed MEA as part of the 10-hour trial promotion on Origin.  I uninstalled it before the 2-hour mark.  Generally, I would be hesitant to talk about a game I hardly got into, but I am passionate about Mass Effect, and I have a lot to say about MEA's issues.  One of the most important things in a narrative-driven game is to hook the player on the premise and stakes early to make them want to see what happens to the characters and world.  MEA fails on this completely.  Compared to the first three games' ensemble cast, MEA's major characters are poorly performed and uninteresting.  The game tries to have this epic inciting incident, but it falls flat on its face because it does a poor job of communicating the stakes of the situation.  Sure, Ryder is *told* that there are thousands of people in cryo-sleep whose survival depends on the mission, but it all comes across as abstract and not urgent.  Also, MEA's combat system takes a huge step back from the refined and fluid system ME3 had.  I completely understand they were trying to make sticking to cover seem less appealing, but when the primary mechanic that is meant to replace that is to hover in mid-air completely exposed and shoot at aliens in cover, it falls flat on its face.  I didn't even actually get to the open-world bit, but I wasn't going to try to put up with it after not enjoying the opening act.

### Metroid: Other M
Other M's combat is competent.  It is worse than most other Metroid games', but it works okay.  Other than that, Other M is an excellent example of bad narrative and characterization dragging a game down.  Other M rehashes the basic premise of Metroid Fusion, minus the alien infection and monstrous doppelganger, but it's placed in the timeline right before Fusion, despite coming out several years later.  The side characters aren't memorable, and the presentation of the relationship between Samus and Adam comes off as abusive and codependent, which is very much at odds with how Adam was remembered in Fusion.  Samus's reputation as this galactic badass is completely undermined.  I can understand the attempt to do a character study on Samus and explore her vulnerabilities, and there are ways to do so without undermining the character as a whole, but Other M completely misses the mark and ends up being one of the more sexist major game releases of the 21st century.  One of the worst scenes is when Samus experiences a PTSD-induced panic attack when confronted by Ridley, the monster who killed her parents when she was a toddler.  However, this scene is made completely farcical when the player realizes that Samus had already faced and defeated Ridley five times as per the events of the previous games on the timeline (this number has risen to six since Other M's release).  Other M was recieved poorly, and I believe rightly so.  I'm just glad that the franchise has started to come back from the hiatus Other M induced.

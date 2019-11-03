# Portfolio

## Professional Projects

### Rogue Company (Sept 2017 - Present), First Watch Games / Hi-Rez Studios

![Rogue Company Box Art](/images/RoCoBoxArt.png)

I currently work as part of Hi-Rez's First Watch Games team on Rogue Company, a third-person shooter featuring elite mercenaries and their top-secret organization.  Gameplay details aren't public yet, but the game is in Unreal 4 and will be available on PC, Switch, PlayStation 4, and Xbox One.  You can see more about the game at [RoCo's website](https://www.roguecompany.com).

Also, here's the [reveal trailer](https://www.youtube.com/watch?v=ybR34uYuLr0).

### Realm Royale (Jun 2018 - Aug 2018), Hi-Rez Studios

![Realm Royale Logo](/images/RealmLogo.png)

Realm Royale is a fantasy third-person battle royale, loosely based on Paladins.  Starting life as a game mode within Paladins, Realm Royale runs on Unreal Engine 3.  My team was briefly brought on to assist the Realm Royale team as the game exploded in popularity.

During the handful of weeks I worked on the project, my major responsibilities were adding new gameplay systems and improving console gameplay feel.  As part of this effort, I built or helped to build:

* An entirely new class, complete with new abilities, a passive, and a weapon.
* A completely reworked aim assist system from that inherited from Paladins' codebase.
* Fixes for various console certification failures around network connectivity loss.

Having to step backwards into Unreal 3 was a challenge, with its idiosyncrasies compared to Unreal 4, specifically surrounding UnrealScript and its status as a quasi-header for native code.  The research and work I did with our lead designer on aim assist really helped inform both of us on how to make it feel good while also being imperceptible.  Getting the console versions ready for certification was excellent practice for working on that moving forward with future projects, as I had moved off of the Hand of the Gods team before console cert passes for that game started.

Realm Royale was released into Steam Early Access in early June 2018 and has since launched on Xbox One, PlayStation 4. and Nintendo Switch.  You can see more about the game at the [Realm Royale website](https://www.realmroyale.com/).

### Hand of the Gods: Smite Tactics (May 2017 - Sept 2017), Hi-Rez Studios - Windows, Xbox One, PlayStation 4
![HotG key art](/images/HotGSplash.png)

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

Hand of the Gods: Smite Tactics was fully released in February 2018 and was available on Windows, Xbox One, and PlayStation 4.  It is no longer available for download and will no longer be playable on 1 January 2020.

### Descent (Jun 2015 - Apr 2017), Descendent Studios - Windows, Mac, Linux
![A player's Torch and a hostile AI Predator face off within the Charon facility](/images/DescentAction.jpg)

Descent (formerly Descent: Underground) was a first person shooter where players control drones within asteroids to fight over limited resources needed by a dying Earth taken over by gigacorporations.  Battles are fought in all six degrees of freedom as drones stay alive by dodging incoming projectiles.

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

Descent's game code was interesting in that it was done almost entirely in Blueprint, allowing for extremely rapid iteration, which we felt was especially necessary for such a small team on a crowdfunded budget.  Looking back, however, there were some serious limitations that could have been overcome by moving the codebase to C++ early in development.

In addition, I was also responsible for supporting the game as a live product, providing minor game design as part of team-wide discussions, supporting design and art integration, and community interaction as part of our open development.

Descent was available in Early Access, but has since been delisted.  While development continued after I started working at Hi-Rez, it doesn't seem likely the game will ever see the light of day.

[See gameplay from before I left the project here.](https://www.youtube.com/watch?v=MiGZi3fufEA)

### Student Projects
I've squirrelled away my student work onto [a separate page](/studentportfolio).

## Technical Experience  

### Unreal Engine 4
UE4 is what I've worked within for my entire career up to this point.  It's my favorite engine I've worked with thus far.  Both Blueprint and Unreal's spin on C++ are very familiar to me, having done gameplay and UI programming in both.  UE4 provides very powerful tools that make all sorts of games possible.  I've worked on a 6DoF shooter and a card game in UE4, and it works excellently in both cases.  I can understand why so many games are hopping on the UE4 wagon, from fighting games like SoulCalibur 6 to RPGs like the Final Fantasy VII remake to massive-scale shooters like Fortnite and PlayerUnknown's Battlegrounds.

### Unity 4
Most of my student projects were in Unity, but I haven't used it since.  That doesn't mean I don't have good things to say about it.  I think it has UE4 beat in terms of pure 2D games, given Unreal's languishing Paper2D plugin.  It worked great for me in college, and there are plenty of great games that make incredible use of it, such as Guns of Icarus Online and Superhot.
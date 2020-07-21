# Portfolio

* [Professional Projects](#professional-projects)
  * [Rogue Company](#rogue-company)
  * [Realm Royale](#realm-royale)
  * [Hand of the Gods](#hand-of-the-gods-smite-tactics)
  * [Descent](#descent)

* [Student Projects](#student-projects)

* [Technical Experience](#technical-experience)
  * [Unreal Engine 4](#unreal-engine-4)
  * [Unity 4](#unity-4)

## Professional Projects

### Rogue Company
#### (Sept 2017 - Present), First Watch Games / Hi-Rez Studios - Windows, Xbox One, PlayStation 4, Nintendo Switch

![Rogue Company Box Art](/images/NewRoCoLogo.png "Rogue Company Logo")

Rogue Company is a near-future third-person tactical-action shooter, featuring an organization of globetrotting mercenaries who use their public image to bolster their reputation.  Gameplay wise, RoCo is if you took a game that's somewhere between CS:GO and Rainbow Six Seige, but then made it third-person and significantly faster.  Like all modern Hi-Rez titles, RoCo will be free-to-play.

I was one of the first people pulled off of Hand of the Gods to start the Rogue Company project, back in fall 2017.  Having been with the project since the very beginning, I've had a hand in a significant portion of the game's development.  As of writing, RoCo has just launched into beta.  In the almost three years I've been on the project, I've contributed to the following major systems:

* UI groundwork by way of bringing over (and generalizing) much of the architecture we built for Hand of the Gods, including gamepad navigation, widget focus stack, and interfacing with the Hi-Rez proprietary backend
* Vaulting/mantling system
* Gyroscopic aiming
* Aim assist
* Camera management, including maintaining the focal point through camera transitions
* Shoulder swap and procedural pose mirroring
* Lag compensation for both hitscan and projectiles
* Client-side prediction for abilities, movement modes, and other responsiveness-sensitive player actions
* Match phase and timer management
* Networked destructibles (like glass)
* Procedural run cycle speed and orientation warping
* On-screen markers for world locations
* Contextual ping, a la Apex Legends
* Runtime physics asset merging

Rogue Company was launched into pay-in beta on 20 July 2020 simultaneously on Windows (via Epic Games Store), Xbox One, PlayStation 4, and Nintendo Switch.  You can see more about the game at [RoCo's website](https://www.roguecompany.com).

See gameplay from RoCo's first public beta release, [CB 0.47](https://www.youtube.com/watch?v=ZaapvrT2ni4).  The video says "Alpha Footage", but it was from the release that went on to be the first beta.

### Realm Royale
#### (Jun 2018 - Aug 2018), Hi-Rez Studios - Windows, Xbox One, PlayStation 4, Nintendo Switch

Realm Royale is a fantasy third-person battle royale, loosely based on Paladins.  Starting life as a game mode within Paladins, Realm Royale runs on Unreal Engine 3.  My team was briefly brought on to assist the Realm Royale team when the game exploded in popularity after it went into open beta in summer 2018.

During the six weeks I worked on the project, my major responsibilities were adding a new class, improving console gameplay feel, and minor certification work.

Realm Royale was released into Steam Early Access in early June 2018 and has since launched on Xbox One, PlayStation 4. and Nintendo Switch.  You can see more about the game at the [Realm Royale website](https://www.realmroyale.com/).

### Hand of the Gods: Smite Tactics
#### (May 2017 - Sept 2017), Hi-Rez Studios - Windows, Xbox One, PlayStation 4
![HotG key art](/images/HotGSplash.png "Hand of the Gods Key Art")

Hand of the Gods is a spin-off of the popular MOBA Smite, combining the casual fun of collectable card games with the mind-games of turn-based tactics, tied together with Smite's colorful cast of deities from around the world.  It's been described as a hybrid between Hearthstone and modern XCOM, which is not an unfair comparison, in my opinion.  Like its parent game, HotG is free-to-play.

Hand of the Gods was built in Unreal Engine 4 over the course of about a year and a half.  I joined the project as a gameplay programmer, but I quickly moved over to UI work, as my previous experience with Unreal Motion Graphics was vital to the project.  As part of the effort to replace the old Coherent-based UI with a new UMG-based one, I was responsible, in part or in whole, for the following client-side features over the months I was on the project:

* Settings
* Front-end tutorial
* Gamepad support
* Player progression
* Social features
* In-game store
* Customization
* Display and navigation of cards within the player's hand

I learned a lot about Unreal Engine working on HotG, especially regarding UI.  Even though I knew a lot about UMG, I learned so much more about how to manage and navigate widgets.  Descent: Underground's UI was severely hampered by having to exist solely within the confines of Blueprint, because there was so much to be gained by putting the widget management on a C++ backbone.

Hand of the Gods: Smite Tactics was fully released in February 2018 and was available on Windows, Xbox One, and PlayStation 4.  It is no longer available for download, and its servers were shut down in January 2020.

### Descent
#### (Jun 2015 - Apr 2017), Descendent Studios - Windows, Mac, Linux
![Descent key art](/images/DescentAction.jpg "Deep within Charon, a Torch and Predator face off.")

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

Descent was available in Early Access, but has since been delisted.  While development continued after I started working at Hi-Rez, it has since fallen into a legal battle, so it doesn't seem likely the game will ever see the light of day.  Descent's online servers and its website shut down some time in 2019.

[See gameplay from before I left the project here.](https://www.youtube.com/watch?v=MiGZi3fufEA)

### Student Projects
I've squirrelled away my student work onto [a separate page](/studentportfolio).

## Technical Experience  

### Unreal Engine 4
UE4 is what I've worked within for my entire career up to this point.  It's my favorite engine I've worked with thus far.  Both Blueprint and Unreal's spin on C++ are very familiar to me, having done gameplay and UI programming in both.  UE4 provides very powerful tools that make all sorts of games possible.  I've worked on a 6DoF shooter and a card game in UE4, and it works excellently in both cases.  I can understand why so many games are hopping on the UE4 wagon, from fighting games like SoulCalibur 6 to RPGs like the Final Fantasy VII remake to massive-scale shooters like Fortnite and PlayerUnknown's Battlegrounds.

### Unity 4
Most of my student projects were in Unity, but I haven't used it since.  That doesn't mean I don't have good things to say about it.  I think it has UE4 beat in terms of pure 2D games, given Unreal's languishing Paper2D plugin.  It worked great for me in college, and there are plenty of great games that make incredible use of it, such as Guns of Icarus Online and Superhot.
# Portfolio

* [Professional Projects](#professional-projects)
  * [Doom: The Dark Ages](#doom-the-dark-ages)
  * [Doom Eternal](#doom-eternal)
  * [Rogue Company](#rogue-company)
  * [Realm Royale](#realm-royale)
  * [Hand of the Gods](#hand-of-the-gods)
  * [Descent](#descent)

* [Personal Projects](#personal-projects)
* [Student Projects](#student-projects)

* [Technical Experience](#tech-experience)
  * [idTech](#idtech)
  * [Unreal Engine 4](#ue4)
  * [Unity 4](#unity)

## Professional Projects

### Doom: The Dark Ages {#doom-the-dark-ages}
#### (Apr 2021 - Present), id Software - Windows, XSX\|S, PS5

![Doom: The Dark Ages logo](/images/dark_ages_logo.png "Doom: The Dark Ages Logo")

*Doom: The Dark Ages* is an upcoming sci-fi/fantasy first-person shooter from the genre-defining *Doom* franchise.  A prequel to *Doom (2016)*, *The Dark Ages* explores the Doom Slayer's past, fighting the legions of Hell in a dark fantasy setting.

As it is not yet available, I am currently unable to share details of my work on *The Dark Ages*.  The game is currently slated to launch in 2025 on Windows, Xbox Series X\|S, and PlayStation 5.

See the [world premiere trailer from the 2024 Xbox Games Showcase](https://www.youtube.com/watch?v=4tk8lkmYGWQ).

### Doom: Eternal {#doom-eternal}
#### (Apr 2021 - Oct 2021), id Software - Windows, Stadia, XB1, XSX\|S, PS4, PS5, Switch

![Doom Eternal logo](/images/DoomEternalLogo.png "Doom Eternal Logo")

*Doom Eternal* is a sci-fi first-person shooter from the genre-defining *Doom* franchise.  The Doom Slayer continues his fight against the legions of Hell and those who have aligned with it for power.  Expanding and refining on the gameplay of *Doom (2016)*, *Eternal* revels in its high-mobility, push-forward combat.

I started at id at the start of the second year of post-launch support for *Eternal*, just after the release of its second DLC pack, *The Ancient Gods: Part Two*.  I provided bugfixes and contributed to the development of the Horde Mode that launched as part of "Patch 6.66", including spearheading visual debugging via imGui.

*Doom Eternal* launched on 19 March 2020 simultaneously on Windows, Stadia, Xbox One, and PlayStation 4.  It was later ported to Nintendo Switch on 8 December 2020 and subsequently ported to Xbox Series X\|S and PlayStation 5 (with ray-traced reflections that simultaneously came to PC) on 29 June 2021.

See the [trailer for "Patch 6.66"](https://www.youtube.com/watch?v=69a0hZVgIU0), which debuted Horde Mode.

### Rogue Company {#rogue-company}
#### (Sept 2017 - Mar 2021), First Watch Games / Hi-Rez Studios - Windows, XB1, XSX\|S, PS4, PS5, Switch

![Rogue Company Box Art](/images/NewRoCoLogo.png "Rogue Company Logo")

*Rogue Company* is a near-future third-person tactical-action shooter, featuring an organization of globetrotting mercenaries who use their public image to bolster their reputation.  Gameplay wise, *RoCo* is if you took a game that's somewhere between *Counter Strike* and *Rainbow Six Seige*, but then made it third-person and significantly faster.  Like all modern Hi-Rez titles, *RoCo* is free-to-play.

I was one of the first people pulled off of *Hand of the Gods* to start the *Rogue Company* project, back in fall 2017.  Having been with the project since the very beginning, I've had a hand in a significant portion of the game's development.  Over the three years I was on the project, I contributed to the following major systems:

* UI groundwork by way of bringing over (and generalizing) much of the architecture we built for *Hand of the Gods*, including gamepad navigation, widget focus stack, and interfacing with the Hi-Rez proprietary backend, all of which set the UI team up for success once they finished *HotG*.
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
* Contextual ping, a la *Apex Legends*
* Runtime physics asset merging

*Rogue Company* was launched into open beta on 1 October 2020 simultaneously on Windows (via Epic Games Store), Xbox One, PlayStation 4, and Nintendo Switch.  It was later ported to Xbox Series X\|S and PlayStation 5 (25 Nov 2020 and 30 Mar 2021, respectively).  You can see more about the game at [the *Rogue Company* website](https://www.roguecompany.com).

See [the "Rogue Reveal" for Kestrel](https://www.youtube.com/watch?v=IfRdjNr4pzk), the last Rogue I worked on before leaving Hi-Rez.  Kestrel was released as part of the Year 1, Season 1 update.

### Realm Royale {#realm-royale}
#### (Jun 2018 - Aug 2018), Hi-Rez Studios - Windows, XB1, PS4, Switch

*Realm Royale* is a fantasy third-person battle royale, loosely based on the *Paladins* intellectual property.  Starting life as a game mode within *Paladins*, *Realm Royale* runs on Unreal Engine 3.  My team was briefly brought on to assist the *Realm Royale* team when the game exploded in popularity after it went into open beta in summer 2018.

During the six weeks the *RoCo* team and I helped with the project, my major responsibilities were adding a new class, improving console gameplay feel, and minor certification work.

*Realm Royale* was released into Steam Early Access in early June 2018 and has since launched as a free-to-play title on Xbox One, PlayStation 4. and Nintendo Switch.  You can see more about the game at [the *Realm Royale* website](https://www.realmroyale.com/).

### Hand of the Gods: Smite Tactics {#hand-of-the-gods}
#### (May 2017 - Sept 2017), Hi-Rez Studios - Windows, XB1, PS4
![HotG key art](/images/HotGSplash.png "Hand of the Gods Key Art")

*Hand of the Gods* was a spin-off of the popular MOBA *Smite*, combining the casual fun of collectable card games with the mind-games of turn-based tactics, tied together with Smite's colorful cast of deities from around the world.  It was described as a hybrid between *Hearthstone* and modern *XCOM*, which is not an unfair comparison, in my opinion.  Like its parent game, *HotG* was free-to-play.

*Hand of the Gods* was built in Unreal Engine 4 over the course of about a year and a half.  I joined the project as a gameplay programmer, but I quickly moved over to UI work, as my previous experience with Unreal Motion Graphics was vital to the project.  As part of the effort to replace the old Coherent-based UI with a new UMG-based one, I was responsible, in part or in whole, for the following client-side features over the months I was on the project:

* Settings
* Front-end tutorial
* Gamepad support
* Player progression
* Social features
* In-game store
* Customization
* Display and navigation of cards within the player's hand

I learned a lot about UE4 working on *HotG*, especially regarding UI.  Even though I knew a lot about UMG, I learned so much more about how to manage and navigate widgets.  *Descent's* UI was severely hampered by having to exist solely within the confines of Blueprint, because it turned out there was so much to be gained by putting the widget management on a C++ backbone.

*Hand of the Gods: Smite Tactics* was fully released in February 2018 and was available on Windows, Xbox One, and PlayStation 4.  It is no longer available for download, and its servers were shut down in January 2020.

### Descent {#descent}
#### (Jun 2015 - Apr 2017), Descendent Studios - Windows, Mac OS, Linux
![Descent key art](/images/DescentAction.jpg "Deep within Charon, a Torch and Predator face off.")

*Descent* (formerly *Descent: Underground*) was a first person shooter where players control drones within asteroids to fight over limited resources needed by a dying Earth taken over by gigacorporations.  Battles are fought in all six degrees of freedom as drones stay alive by dodging incoming projectiles.

*Descent* was my first professional project and first experience working within Unreal Engine 4.  I was a gameplay programmer on the project, responsible for drawing up design for and implementing such systems as the following:

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

*Descent's* game code was interesting in that it was done almost entirely in Blueprint, allowing for extremely rapid iteration, which we felt was especially necessary for such a small team on a crowdfunded budget.  Looking back, however, there were some serious limitations that could have been overcome by moving the codebase to C++ early in development.

In addition, I was also responsible for supporting the game as a live product, providing minor game design as part of team-wide discussions, supporting design and art integration, and community interaction as part of our open development.

*Descent* was available as a purchased title in Early Access, but has since been delisted.  While development continued after I started working at Hi-Rez, it has since fallen into a legal battle, so it doesn't seem likely the game will ever see the light of day.  *Descent's* online servers and its website shut down some time in 2019.

[See gameplay from before I left the project here.](https://www.youtube.com/watch?v=MiGZi3fufEA)

### Personal Projects {#personal-projects}
I've created [a separate page](/personalportfolio) for talking about my personal projects.

### Student Projects {#student-projects}
I've squirrelled away my student work onto [a separate page](/studentportfolio).

## Technical Experience {#tech-experience}

### idTech {#idtech}
Since joining id Software, I have been working inside id's in-house engine, idTech, specifically version 7, which powered *Doom Eternal*, and newer.  Each version of idTech is tailored to the specific game which it powers.

### Unreal Engine 4 {#ue4}
For the first six years of my career, I worked almost exclusively in UE4, and I had a fantastic time operating within that environment.  Both Blueprint and Unreal's spin on C++ are very familiar to me, having done gameplay and UI programming in both.  UE4 provides very powerful tools that make all sorts of games possible.  I've worked on a 6DoF shooter, a card game, and a third-person shooter in UE4, and it works excellently in all of those cases.  I can understand why so many games are hopping on the UE4 wagon, from fighting games like *SoulCalibur 6* to RPGs like the *Final Fantasy VII* remake to massive-scale shooters like *Fortnite* and *PlayerUnknown's Battlegrounds*.

### Unity 4 {#unity}
Most of my student projects were in Unity, but I haven't used it since.  That doesn't mean I don't have good things to say about it.  I think it has UE4 beat in terms of pure 2D games, given Unreal's languishing Paper2D plugin.  It worked great for me in college, and there are plenty of great games that make incredible use of it, such as *Guns of Icarus Online* and *Superhot*.
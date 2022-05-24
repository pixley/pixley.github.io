# Personal Projects
I have multiple public repositories on [my GitHub profile](https://github.com/pixley), but there are some that I feel are worth calling out in particular.

* [TimelineBuilder](#timeline-builder)
* [Ultra Spicy RPG Bot](#discord-bot)
* [Pokémon Streaming Tools](#pokemon-streams)

## TimelineBuilder (Mar 2022 - Present) {#timeline-builder}
[TimelineBuilder](https://github.com/pixley/TimelineBuilder) is an ongoing project to build a desktop program that allows worldbuilders to create and visualize timelines for their settings.

The reason I started making TimelineBuilder is that my wife, who GMs a Pathfinder2e game for me and some friends, was having trouble with the lack of timeline functionality found in many publicly available worldbuilding suites, such as WorldAnvil, particularly in regard to the fact that the "timelines" are presented more as glorified lists than actual timelines.  After scouring the internet myself and finding nothing that quite achieved our vision, I resolved to rectify that gap in the market with a free, open-source, and customizeable app.

My vision for TimelineBuilder is for it to be a universal timeline tool, able to work with any calendar system provided to it (via script plug-ins), allowing worldbuilders to create robust timelines for their worlds and to see the events, periods, and eras of that timeline at-scale.

TimelineBuilder is being written primarily in C++, with scripts done in Python 3.

## Ultra Spicy RPG Bot (Sept 2021 - Mar 2022; may resume)  {#discord-bot}
Originally forked from [discord-audio-pipe](https://github.com/QiCuiHub/discord-audio-pipe), the [Ultra Spicy RPG Bot](https://github.com/pixley/discord-audio-pipe) is a Discord bot I made to assist in my friends' Pathfinder experience.  I originally created it in response to the shutting down of music-playing Discord bots (such as Rythm and Groovy) in early 2022.

Its main feature is serving as a pipe for audio from a PC to the Discord voice channel to which the bot is connected.  This makes it a suitable method of providing background music to a Discord channel.  I primarily use it in its VBAN mode, which uses VBAN audio streaming to transmit an audio feed from my personal PC to a server on which the bot is actually running.  This allows the bot to have uptime independent of my own.

A secondary feature I grafted onto it is to handle a lot of the math inherent in making secret rolls against an entire party's worth of characters (six, in our case).  It takes in and stores party information, including various modifiers and feats, which is then compared against when making one of a handful of supported secret checks.  I added this because my wife is not confident when it comes to math, and doing all that work in an amount of time to provide natural feedback is difficult for her.

Both features are largely controlled by text commands via Discord, allowing the bot to run and accept changes without someone (read: me) having to log into the server hosting it.

The Ultra Spicy RPG Bot is written in Python 3 to take advantage of [Discord.py](https://discordpy.readthedocs.io/).  The name comes from our larger group of Hi-Rez friends from which we gathered our Pathfinder party: Ultra Spicy.

## Pokémon Streaming Tools (Sept 2014 - Mar 2015)  {#pokemon-streams}
Back in college, I got really into Twitch Plays Pokémon, to the point where I decided that it would be fun to restream the feed of the *Pokémon Stadium 2* matches and provide play-by-play commentary over them.  Due to the amount of variables that can decide which player has the advantage for any given matchup, I decided to whip up [StadiumStats](https://github.com/pixley/StadiumStats) in Python to provide the competitors' stats and moves at-a-glance.

While on that streaming commentary kick, I was introduced to the concept of Nuzlocke runs by my then-girlfriend/now-wife.  I decided I wanted to try streaming that, but I wanted to have an overlay to allow viewers to see at-a-glance what the state of my party was.  In developing [Pokevis](https://github.com/pixley/Pokevis), I switched over to using C++ with SMFL to build the display window that would serve as an overlay.

A few months later, TPP switched its inter-run game from *Stadium 2* to *Pokémon Battle Revolution*, and, wanting to resume my commentary bit, I wrote [RevolutionStats](https://github.com/pixley/RevolutionStats).  With RevolutionStats, I took what I had learned from Pokevis to build a new stat display window.

I'll be honest, the code I wrote for these three projects was pretty bad, and it turns out my performance as a streamer could charitably be described as mediocre.  However, I believe these projects are worth including here because they were projects that I put enough into to make them useable, if only for myself.
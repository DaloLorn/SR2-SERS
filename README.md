# SERS

A turn-based conversion mod for Star Ruler 2, based primarily on the Rising Stars mod (content-wise) and Space Empires 5 (mechanically speaking).

## What's this all about?

Star Ruler 2, as any of its players know, is a [real-time 4X](https://en.wikipedia.org/wiki/4X#Real_Time_Hybrid_4X) similar to Sins of a Solar Empire, only a bit more on the 4X side of the spectrum. Unfortunately, its real-time nature makes a lot of things unfeasible, either due to computational requirements or the fact that a human being can only deal with so many things at any given moment.

SR2 is also similar in a lot of ways to the [Space Empires](https://en.wikipedia.org/wiki/Space_Empires) games - at least, what those games (particularly SE5) would be like if they were made using today's graphics and computational capabilities. As a longtime fan of Space Empires 4 and 5, I'm understandably intrigued by those similarities, and eager to expand them - but as I already explained, there's only so much a PC or person can do, so either the complexity or the playability of the game have to go... neither of which is acceptable.

So, this project is basically an attempt to use SR2's extreme moddability (SE5 pales in comparison to SR2, it's *that* moddable) to create a sort of 'Space Empires 6' inside the Starflare engine.

## What's it going to be like?

Initially, it'll basically be turn-based SR2. The content will be the same, the gameplay mechanics will be as close to SR2 as possible... but distances, the passage of time and everything related to them will be different.

The biggest improvements over SE5 will probably be in the multiplayer and graphics departments (well, 3D graphics, anyway - the 2D side varies in quality), and the gameplay will probably take more from SR2 and specifically Rising Stars. Tactical combat, for instance, will look exactly like it does in SR2 (though perhaps with different, SE5-like notions of what a 'fleet' is, and a better sense of scale).

Economy, research and diplomacy will probably resemble SR2 in the early builds, but who knows where it might go after that. I've got half a mind to take the SE5 soundtrack, seeing as its pace is a bit better for this kind of game (besides, Rising Stars already uses a few subsystem icons from that game, Malfador's artists were consistently good with their 2D art), but that's probably as far as it'll go.

Eventually (as in, 'after 1.0'), the plan is to continue developing Rising Stars for SERS.

## What's the point of this? Yes, yes, more complexity, but why bother?

Several reasons.

- Because I bloody want to. :P
- The SR2 community is fragmented - on the European side, there doesn't seem to be anything left except maybe two or three people, while the American side... truthfully, I don't know too much about that part of the world, but it sounds like they're not doing much better off either. Ideally, SERS will be able to bring them together in a similar fashion to the 'Play-By-Web' service that's undoubtedly had a vital role in keeping the Space Empires community alive to this day. (Citation needed. I lost track of them when spaceempires.net died.)
- A beneficial side-effect of this whole thing is that even if the multiplayer community stays as anemic as it is, I'll have both the knowledge and the opportunity to make the game work in such a way that even the AI will be enough to keep my interest. (Right now, it becomes rather dull if there's no human beings to interact with. The AI's competent, but not active in the same way as a human player - and the rest of the game just doesn't have enough things to do all the time.)
- A project of this scale is A: a good way to build up programming skill without "working for work's sake", for lack of a better term, and B: nice to have on one's CV afterwards, which could be handy in the future.


## Development plans

The rough idea is to follow a path like this:

**Pre-alpha** *(YOU ARE HERE)* - Sort out the core of the engine. At this stage of development, you'll be lucky to get the main menu instead of a black screen when you enter the game, and you probably won't be able to start even the design sandbox without all hell breaking loose.

**Alpha** - By now, it should be possible to take turns and see the galactic map. Now it's time to get basic gameplay up and running, hook everything together until it is at least *sort of* playable. At this stage, the sandbox should work again, but actually playing a proper match is questionable. (This is also the first stage that will get released on the Steam Workshop.)

**Beta** - All of the really big features have been dealt with. The game more or less feels like 'SR2 with turns' now. All that's left is adding in minor features (for example, flexible turn speeds) and polishing everything up.

**Release 1** - SERS 1.0 is done and uploaded to both the Workshop and ModDB. After a round of applause for everyone involved, and a lot of partying, it's time to move on to the next stage.

**Release 2, and into the future** - SERS 2.0. (Alternatively, 'SERS2' - or to perpetuate the original pun, '2 SERS'/'2SERS'. :P) SERS1 will remain uploaded as its own thing - 2SERS will be a separate mod derived from the 1.0 engine. 1.0 will keep getting bugfixes and QoL updates, but its gameplay and content will not be changed in any significant way.

2SERS will basically be an amalgamation of the latest versions of the Alternate Balance Expansion Mod and its successor, Rising Stars - taking the best of both mods and expanding them further towards the project's ultimate goal.

## I want to contribute, how do I do that?

There's several ways you can help with this project, if you have the time and willingness to do so.

### Development

You can help develop the mod, either in the scripting department (this is a *huge* project with plenty of scripts to write), or with porting/creating content.

Requirements:

- Presumably a copy of Star Ruler 2? ;)
- A Git client. People with no Git experience should probably pick up Atlassian's SourceTree client, because I'm using that and can help guide others through the basics. People who already use Git elsewhere can just use whatever client they had before.
- A half-decent understanding of the English language. You're not going to be much use if I can't talk to you, after all. :P

Programmer-specific requirements:

- An understanding of algorithms and how to make them.
- Preferably some knowledge of AngelScript syntax and Star Ruler 2 script files. Really, the algorithm part is *a lot* more important.

UI programmer-specific requirements:

- All of the programmer-specific requirements
- The ability to design a UI without a [WYSIWYG](https://en.wikipedia.org/wiki/WYSIWYG) editor. (Or, better yet, the ability to program such an editor for the SR2 UI, which will earn the gratitude of every wannabe UI modder in this community - myself included.)

The requirements for a content designer are somewhat broader and don't need to be met *simultaneously*, I suppose:

- Ideas.
- Familiarity with either the SR2 mod editor or the files it generates.
- Artistic capabilities, either for graphics or sounds or stuff.

### Testing

Once the mod enters the alpha stage, there's going to be a need for people to kick the engine around and see what it does. This is going to become increasingly important as development continues, because the butterfly effect is (unfortunately) applicable to large codebases. :P

Requirements:

- A *Steam* copy of Star Ruler 2, because of the need for Workshop access.
- Alternatively, a Git client. (See above.)

### Suggestions

If you have an idea on how to make the mod better, just say so.

## How does one get the mod from GitHub?

If you just want to play around with the current version, you can download a .zip file containing the mod's files. Just copy the 'SERS' folder into Star Ruler 2/mods.

If you want to help develop the mod, or just regularly pick up updates from GitHub (for example, if you're a tester), you need to clone the repository in a Git client, then follow the instructions outlined by Darloth at the bottom of [this page](https://github.com/Alarcarr/Rising-Star/issues/20), with these alterations:

- Instead of "Alarcarr/Rising-Star", use "DaloLorn/SR2-SERS". I probably don't have to tell you this, but better safe than sorry.
- Replace all instances of "Rising Stars" with "SERS".

## Contact information

If you need help, or have some feedback to give, you can go to the Discord chat [here](https://discord.gg/gMJbpaJ). I always read everything, though if I'm away from the computer (or the PC's off altogether) I won't be able to respond right away. Look for the Protoss with the purple name and the oversized helmet. :P
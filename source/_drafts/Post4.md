---
title: Post4
tags:
---

With the onslaught of midterms, projects, Thanksgiving, and the new season of Stranger Things on Netflix, time has been hard to come by in the last few weeks. It's been more than a month since I last touched Falcomaster. I did not expect to get done with Falcomaster any time soon, but I did not expect to get so busy in this part of the semester. Thank you guys for your patience with me! :)

While I haven't been able to work on the project, I have been thinking about it. Recently, I realized I have made a mistake in my initial draft of Falcomaster, and need to make a crucial adjustment. I think you guys will like it :D
<!-- more -->

### The Problem: Not Enough Time!

Originally, I was going to use my own gameplay as training data for the program. Given enough game footage of playing the game, paired with what inputs I used, Falcomaster will eventually mimic my playstyle.

This works in theory, but there's a problem: how much footage do I need?

I don't have any concrete numbers for how long I would need to play in order to get enough footage, but I believe it will take a long time. That's no good!

If only someone has already recorded years of their own footage that I can use for this project! Oh wait....

### The Solution: VODS

What if I can train Falcomaster on the many vods of game footage on YouTube and Twitch? The footage already exists, so I don't need to create more, and there's tons of it out there!

But there comes a problem. Originally, I wanted to use my own footage because I can pair the video frames to whatever inputs I make on a controller. That will instruct Falcomaster not only what IS the right move to make, but HOW to make it happen. It's like when your friend tells you to castle in chess, but you can't tell the different between a pawn and a knight. You need to have basic knowledge first.

By using existing vods, I won't have these button inputs to go with it. How am I supposed to train Falcomaster now?

As it turns out, it's an easy fix: more training! Let me explain.

It's possible to first train Falcomaster to recognize the visual effects of button inputs ("What does Falco's forward smash attack look like?"). Once it can recognize the moves, Falcomaster can then be trained on the vods. Now, when it looks at the vods, it knows what it's looking at!

This two-layered training approach might be the solution to fix this issue, so I will be directing myself toward this answer.

### The Implications of this New Solution

Not only does this proposal solve a key problem in Falcomaster, it opens new opportunities.

Given the number of vods out there for Melee, it may be possible to get incredibly accurate representations of players. Sure, we might not be able to get enough data for some of the more obscure players out there (who's heard of Benji, amiright?). But high-profile players with years of investment in the scene, such as Zhu, Mang0, and Mew2King to name a few, we might have a good chance.

Theoretically, Falcomaster can craft replicas of these top players, which can be exciting for the smash community. Does this mean you could play friendlies with any player, any time you want, as long as the player has enough vods for Falcomaster? Maybe Falcomaster can help players in regions without much top-level representation, providing them with substitute training partners that they wouldn't have access to otherwise.

This could actually be meta-shifting at the highest echelon of competitive Melee. If the replicas are accurate, they can serve as practice partners for even top players. What if Armada wants more practice against Hungrybox, but Hungrybox never wants to play with Armada? If Armada can play a replica of Hungrybox instead, would that give him an advantage? Could punish game or neutral be practiced against these replicas in a manner never done before?

OK, I'm definitely hyping things up here, and there's no guarantee that any of this could happen. But it would be seriously cool, and I can't wait to get back to actually working on this :D
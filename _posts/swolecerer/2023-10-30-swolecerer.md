---
layout: post
title: Swolecerer
date: 2023-10-30 20:43 -0400
image:  /assets/img/swolecerer/cover.png
---

# Introduction
This concept is a result of DevLUp UF's Fall 2023 game jam, which was itself a 'practice run' in anticipation for the state wide DevLUp *Wargames*, later in November. 

Leading up to the jam, I wanted a small team where I had an artist or two, but have two of my CS friends for programmers, as I've been trying to get them into game development for a while. This ended up becoming a 9 person team in total as we picked up a lot of people who were otherwise without a team.

The revealed theme was ***impaired***, and we settled on the following idea:

You're a wizard who was locked in a dungeon for grand mischief. You have a magical ball and chain attached to your ankle, limiting all your wizard abilities. Left to rot in a dungeon for 10 years, you did *crazy pushups* until you got super buff. Throw your ball and chain and ragdoll behind it to fly through the castle and escape.

# Overscoped...
The most intriguing part of this to me was figuring out ragdoll physics. The [Godot tutorial](https://docs.godotengine.org/en/stable/tutorials/physics/ragdoll_system.html) for it seemed simple enough, so I declared it within scope for the jam.
> Other items I declared 'within scope' for a weekend day game jam:
> - Learning a new mapping tool ([TrenchBroom](https://trenchbroom.github.io/))
> - Maintaining a Kanban board for my 7 person team
> - Teaching 3 of those 7 how to use Godot
> - Finding something for the non-artist/non-programmer people to do
> - Sleeping more than 4 hours
>
> **Conclusion:** I can not scope.

Implementing the ragdoll mechanics would prove to take the majority of my time. While this means that our end product was nowhere close to playable by the time the deadline rolled around, I'm wanting to extend development. I learned plenty, and throwing yourself around is already kind of fun.
![Alt text](/assets/img/swolecerer/img1.png)
Look at how he flies!


# Plans for the future
- Better level design using all of TrenchBroom's capabilities
- Items for the player to collect (end goal of the game)
- Interactive elements such as breakable blocks, levers, etc.
- Rework the ball and chain physics to be more satisfying and less buggy.
- Figure out exactly where my ragdoll physics went wrong and how to improve it without sacrificing stability.

## Next post...
- Cleaned up visuals for current features
- Collectible item
- Playable demo?

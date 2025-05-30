---
author: MarshmalloQi
pubDatetime: 2025-04-08T20:58:52.737Z
modDatetime: 2025-05-30T09:25:46.734Z
title: Game 2 - Wait
description: A ctf chall involving creative thinking and time manipulation abilities
slug: kashictf/misc/game_2
featured: false
draft: false
tags:
  - kashictf
  - bash
  - rev
  - misc
  - reversing
  - C#
  - Time
  - game development
  - Game
---


# Game 2 - Wait ⏰
**Final Points:** 195


## Description
We made a game.


Flag format: `KashiCTF{your_flag_here};`

## Link -
 [Drive Link](https://drive.google.com/file/d/1GDYmOiW54pPLFxfQaBOOS5IPEAoplFPy/view?usp=drive_link) {Download the game from here} ==> `wait.exe`

----
## Writeup

On downloading the game file,


<img src="/kashictf/game2/images/sus.png" alt="game here">

The logo of the game was `sus`. 😆😆

I ran the command 
```
grep -r "KashiCTF{"
```
but got nothing from it.

<img src="/kashictf/game2/images/nogrep.png" alt="grep won't work here kiddo">

Then I ran it using wine.

<img src="/kashictf/game2/images/waiting.png" alt="game start">

It was a simple game, and its objective was to wait for `48 hours` or `172800 Seconds` for the flag to be revealed.

I could have waited for the flag to be revealed automatically after 2 days but the CTF competition was for 24 hours only in itself.

So, now I could have used a tool like [Cheat Engine](https://www.cheatengine.org/) or just try changing the Date of my system to see if it works.

<img src="/kashictf/game2/images/bef.png" alt="before the date change">

and after changing the date to 2 days later, I got

<img src="/kashictf/game2/images/af.png" alt="After the date change">

the flag !!!

It was very easy after all.

We could have also used Cheat engine to change the time_remaining attribute 

---
## Flag

```
KashiCTF{Ch4kr4_Vyuh}
```                 


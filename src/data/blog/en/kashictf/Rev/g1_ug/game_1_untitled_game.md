---
author: MarshmalloQi
pubDatetime: 2025-04-08T20:58:52.737Z
modDatetime: 2025-05-30T09:25:46.734Z
title: Game 1 - Untitled Game

description: A basic ctf chall involving bash scripts and linux scripting
slug: en/kashictf/Rev/g1_ug
featured: false
draft: false
tags:
  - kashictf
  - bash
  - rev
  - reversing
  - C#
  - game development
  - Game
---

# Game 1 - Untitled Game 🎮

**Final Points:** 100


## Description
We made a game.


Flag format: `KashiCTF{your_flag_here};`

## Link -
 [Drive Link](https://drive.google.com/file/d/1bf4WnxE81YIizN2e77x5PrkqGPwllgki/view?usp=drive_link) {Download the game from here} ==> `Challgame.exe`

----
## Writeup

On downloading the files, I ran the command 
```
grep -r "KashiCTF{"
```
Which showed that this string existed inside the binary `Challgame.exe`

so I ran 
```
grep -a "KashiCTF{" Challgame.exe
```

Which gave the flag.
<img src="/kashictf/game-1/images/sol.png" alt="solution">

---
## The Game

I ran it using wine.
 
<img src="/kashictf/game-1/images/wine.png" alt="wine">

It was a simple same where the objective was to escape the trap.

<img src="/kashictf/game-1/images/game.png" alt="game">

on clicking let's begin
<img src="/kashictf/game-1/images/ingame.png" alt="game">

---
## Flag

```
KashiCTF{N07_1N_7H3_G4M3}
```                 


---
layout: project
title: "Spaceout"
date: 2020-06-28 16:00:22 +0800
categories: projects
author: "Tan Kun Sheng"
display_pic: "https://kunshengsite.s3-ap-southeast-1.amazonaws.com/projects/web/spaceout/spaceout.mp4"
short_desc: "Shoot stuff and don't die. Shoot more stuff."
link : "https://kunsheng-games.herokuapp.com/Pages/Game/Intro.html"
techstack: "Javascript 2d canvas API for web game, firebase for highscore db"

# so that links wont break
permalink: "/projects/:title.html"
---

## Background

Spaceout is a endless space shooter where you destroy space stuff to gain gold, then use the gold accumulated to upgrade your ship so that you can destroy more space stuff to earn more gold. 

The game gets progressively harder too. The pace of the game quickens, as well as the enemies' hit points. Control your mouse cursor to move the ship around in order to dodge enemies and their projectiles, and remember to upgrade your ship with the gold accumulated from defeating enemies.

<p class="text-accent">Note: The game might take awhile to load at the start</p>

## 1. Ship Upgrades

<div class="container mx-auto px-2 py-4 table">
    <div class="prose col-8 sm-width-half left">
        <img src="https://kunshengsite.s3-ap-southeast-1.amazonaws.com/projects/web/spaceout/spaceout-upgrades.png" alt="spaceout" />
    </div>
</div>

Clicking on anywhere on the game canvas will bring down a window. This plain looking window with some texts and a few buttons is in fact, your mechanic workshop, I kid you not xD. In here, you will be able to upgrade your asteroid busting spacecraft in 3 ways:

1. The firing rate of the ship's gun. More bullets per second translates to a higher kill rate!
2. Extend the life of your ship. Nothing is more important than living to fight another day.
3. Attaching an additional gun barrel on your ship. Upgradable up to 3 times the fire power!

## 2. Highscores

<div class="container mx-auto px-2 py-4 table">
    <div class="prose col-8 sm-width-half left">
        <img src="https://kunshengsite.s3-ap-southeast-1.amazonaws.com/projects/web/spaceout/spaceout-gameover.PNG" alt="spaceout_highscores" />
    </div>
</div>
All good things come to an end. Similarly, your gun slinging, asteroid killing, ufo busting gig will come to an end eventually in Spaceout as well. But fret not, your spirit lives on forever in the form of, **digits!**

Submit your top score and tell the world how badass you are!

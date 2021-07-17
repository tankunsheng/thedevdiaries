---
layout: project
title:  The NBA Quiz
date:   2020-08-29 16:00:22 +0800
categories: myprojects
type: mobile
author: "Tan Kun Sheng"
display_pic : "https://kunshengsite.s3-ap-southeast-1.amazonaws.com/projects/android/nba_logo_quiz/nba.png"
short_desc: "You call yourself a basketball fan? Are you sure you can name any other player outside of Michael Jordan, Kobe, and Lebron? Prove it!"
link : "https://play.google.com/store/apps/details?id=codeleveling.nbaquiz"
techstack: "Native Android SDK for client app, Firebase for highscores"
---

## Background
I am a huge basketball fan who regularly follows the NBA's pre and post seasons. The NBA Quiz was something that I did entirely out of fun and love for my favourite sport. For the most part, it is just a reskin of "World Logo Quiz", so aside from preparing the new assets, there was minimal work to be done in terms of code.

## Player Images

<div class="container mx-auto px-2 py-4 table">
    <div class="prose col-2 sm-width-half left">
        <img src="https://kunshengsite.s3-ap-southeast-1.amazonaws.com/projects/android/nba_logo_quiz/nba-nosketch.png" alt="nba_quiz_hint" />
    </div>
    <div class="prose col-2 sm-width-half left ml-lg-4">
        <img src="https://kunshengsite.s3-ap-southeast-1.amazonaws.com/projects/android/nba_logo_quiz/nba-nosketch2.png" alt="nba_quiz_player" />
    </div>
    <div class="prose col-2 sm-width-half left ml-lg-4">
        <img src="https://kunshengsite.s3-ap-southeast-1.amazonaws.com/projects/android/nba_logo_quiz/nba-nosketch3.png" alt="nba_quiz_players" />
    </div>
</div>

It was originally meant to be a very simple game where you have to guess the names of the NBA players by looking at their photos. Alas, I was too young, too naive. How could I have thought that face images of NBA star players to be free for use? My first shot at getting the app published on Google Play Store got rejected as it did not meet their Copyright policy. 

This goes to show the importance of testing out your deployment as early as possible. It will help to flush out any unknown unknowns, and things that could have slipped your mind so that they do not catch you by surprise later. The later you discover these overlooked issues, the more time and effort will be needed to rectify them.

For my case, I ended up processing the images with a "sketch" effect and cropped out a portion of the players' facial features. Somehow, this managed to pass Google Play's policies, and the results turned out much better than I had expected.

## Sketchy Stuffs

<div class="container mx-auto px-2 py-4 table">
    <div class="prose col-2 sm-width-half left">
        <img src="https://kunshengsite.s3-ap-southeast-1.amazonaws.com/projects/android/nba_logo_quiz/nba-sketch.png" alt="nba_quiz_sketches" />
    </div>
    <div class="prose col-2 sm-width-half left ml-lg-4">
        <img src="https://kunshengsite.s3-ap-southeast-1.amazonaws.com/projects/android/nba_logo_quiz/nba-sketch2.png" alt="nba_quiz_sketches_player" />
    </div>
</div>

The sketched potraits looked good and added an additional challenge to the game which would have been too easy otherwise. Do check the app out if you're an NBA fan!
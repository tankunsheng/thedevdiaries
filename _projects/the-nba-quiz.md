---
layout: project
title:  The NBA Quiz
date:   2020-05-27 16:00:22 +0800
categories: myprojects
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
        <img src="https://kunshengsite.s3-ap-southeast-1.amazonaws.com/projects/android/nba_logo_quiz/nba-nosketch.png" alt="world_logo_quiz_use_hint" />
    </div>
    <div class="prose col-2 sm-width-half left ml-lg-4">
        <img src="https://kunshengsite.s3-ap-southeast-1.amazonaws.com/projects/android/nba_logo_quiz/nba-nosketch2.png" alt="world_logo_quiz_use_vowel" />
    </div>
    <div class="prose col-2 sm-width-half left ml-lg-4">
        <img src="https://kunshengsite.s3-ap-southeast-1.amazonaws.com/projects/android/nba_logo_quiz/nba-nosketch3.png" alt="world_logo_quiz_hint" />
    </div>
</div>

It was originally meant to be a very simple game where you guess the names of the NBA players by looking at their photos. You could only imagine the pain I felt when after going through the hassle of searching for hundreds of pictures, cropping, editting and including them into the app only to be notified upon app publishing that the app did not meet the standards set out by Google Play's policy.


<!-- This goes to show that you have to deploy early and often to 
I should have taken baby steps and tested things out by using a smaller set of images instead of naively diving head first into development thinking that the images from sources on the internet were free to use after doing some minor editting.

I ended up processing the images and edited them so much that they looked like sketched copies instead of photos. This managed to pass Google Play's policies, but much much more work had to be done to convert all the images into the sketched variants. -->

## Sketchy Stuffs
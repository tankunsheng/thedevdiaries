---
layout: project
title:  World Logo Quiz
date:   2020-05-28 16:00:22 +0800
categories: myprojects
author: "Tan Kun Sheng"
display_pic : "https://kunshengsite.s3-ap-southeast-1.amazonaws.com/projects/android/world_logo_quiz/world_logo_quiz.png"
short_desc: "Just how many logos around the world can you recognize? Unlock new stages as you play. The stages get progressively harder, so let's see how you fare on the all-time leaderboards!"
link : "https://play.google.com/store/apps/details?id=sg.ace.ks.globallogoquiz"
---

## Background
There was a time when quiz games dominated Google Play Store's top downloaded apps. Apps such as "4 pic 1 word", "Logo quiz", "Flag quiz" and other apps of these nature were at one point in time, the most popular apps to make and play. Compared to real full fledged 2d/3d games built with game engines, these games were easier to play and develope.

Putting my own game onto the Google Play seemed like such a cool idea, and so, I went out and tried my hand in making a quiz game with the native android SDK. I also had no ideas how to create graphics or assets, but I figured that I would create them along the way. No matter how awful looking it may be (even to myself) looking back at it now, I am still really glad that I saw it through to the end. Let's go through some of its features. 

## 1. Stage Progression

<div class="container mx-auto px-2 py-4 table">
    <div class="prose col-2 sm-width-half left ">
        <img src="https://kunshengsite.s3-ap-southeast-1.amazonaws.com/projects/android/world_logo_quiz/world-stages.jpg" alt="world_logo_quiz_stages" />
    </div>
    <div class="prose col-2 sm-width-half left ml-lg-4">
        <img src="https://kunshengsite.s3-ap-southeast-1.amazonaws.com/projects/android/world_logo_quiz/world-locked-stages.jpg" alt="world_logo_quiz_locked_stages" />
    </div>
</div>
Game progression is an important element in most games and it is something that incentivizes a player's time spent in the game by providing some sort of feedback reward mechanism. Really, nobody likes having nothing to show for after sinking hours on end into a game. For example, games in the RPG genre reward players with plot progression and a sense of character advancement through gaining levels and obtaining stronger gear.

World Logo Quiz utilizes a simple, unlock as you progress, stage-based system for its game progression. It helps to create some anticipation in players for wanting to eventually unlock all stages and clear the game cause you know, there is nothing like showing off a fully completed <b>World Logo Quiz</b> to your friends right.

## 2. Flexibility in Question Selection
<div class="container mx-auto px-2 py-4 table">
    <div class="prose col-2 sm-width-half left ">
        <img src="https://kunshengsite.s3-ap-southeast-1.amazonaws.com/projects/android/world_logo_quiz/world-question.jpg" alt="world_logo_quiz_single_qns" />
    </div>
    <div class="prose col-2 sm-width-half left ml-lg-4">
        <img src="https://kunshengsite.s3-ap-southeast-1.amazonaws.com/projects/android/world_logo_quiz/world-question-list.jpg" alt="world_logo_quiz_qns_list" />
    </div>
</div>

One of the things that I've learnt after playing some of the 4 Pic 1 Word games was to balance linearity and flexibility. The questions in some of the 4 Pic 1 Word games were entirely un-skippable and needed to be solved sequentially. What made it worse was that there were no ways for players to get help if they had troubles with one particular question. 

I adopted a more flexible approach that allowed players to freely skip to any question of a certain stage. To minimize the likelihood that users might be stuck on a certain question and thus, killing the fun. There are also other mechanics which players can employ to assist them in solving the quiz. These however, need to be earned by solving logos.

## 3. Buy a Hint or Vowel
<div class="container mx-auto px-2 py-4 table">
    <div class="prose col-2 sm-width-half left">
        <img src="https://kunshengsite.s3-ap-southeast-1.amazonaws.com/projects/android/world_logo_quiz/world-usehint.jpg" alt="world_logo_quiz_use_hint" />
    </div>
    <div class="prose col-2 sm-width-half left ml-lg-4">
        <img src="https://kunshengsite.s3-ap-southeast-1.amazonaws.com/projects/android/world_logo_quiz/world-use-vowel.jpg" alt="world_logo_quiz_use_vowel" />
    </div>
    <div class="prose col-2 sm-width-half left ml-lg-4">
        <img src="https://kunshengsite.s3-ap-southeast-1.amazonaws.com/projects/android/world_logo_quiz/world-used-hint-and-vowel.jpg" alt="world_logo_quiz_hint" />
    </div>
    <div class="prose col-2 sm-width-half left ml-lg-4">
        <img src="https://kunshengsite.s3-ap-southeast-1.amazonaws.com/projects/android/world_logo_quiz/world-gain-hint.jpg" alt="world_logo_quiz_gain_hint" />
    </div>
</div>
Gain hint points as you solve the logo questions and stages. These hint points can be used to purchase vowels or unlock hints, both help in offering clues to the answer.
- Vowels unveil the "AEIOU" lettered positions of the logo. Depending on which vowel is chosen, the value of its use can be varied as no letters are revealed if the selected vowel is not part of the word. So, choose wisely.
- Hints are more straightforward, it simply reveals a fact about the entity which the logo identifies. In my personal opinion, buying vowels are more effective.

## 4. Sharing on Social Media for Help
<div class="container mx-auto px-2 py-4 table">
    <div class="prose col-2 sm-width-half left ">
        <img src="https://kunshengsite.s3-ap-southeast-1.amazonaws.com/projects/android/world_logo_quiz/world-share.jpg" alt="world_logo_quiz_share" />
    </div>
    <div class="prose col-2 sm-width-half left ml-lg-4">
        <img src="https://kunshengsite.s3-ap-southeast-1.amazonaws.com/projects/android/world_logo_quiz/world-fb-share.jpg" alt="world_logo_quiz_fb" />
    </div>
</div>
I was really afraid that players will get stuck in the game, having ran out of hints and unable to progress. This was another feature that helps in aiding player progression as well as getting free publicity for the app.

No worries, no one will judge you for not recognizing a particular brand's logo... unless it's Macs.


## 5. Report and Highscores
<div class="container mx-auto px-2 py-4 table">
    <div class="prose col-2 sm-width-half left">
        <img src="https://kunshengsite.s3-ap-southeast-1.amazonaws.com/projects/android/world_logo_quiz/world-report.jpg" alt="world_logo_quiz_report" />
    </div>
    <div class="prose col-2 sm-width-half left ml-lg-4">
        <img src="https://kunshengsite.s3-ap-southeast-1.amazonaws.com/projects/android/world_logo_quiz/world-report2.jpg" alt="world_logo_quiz_report_share" />
    </div>
    <div class="prose col-2 sm-width-half left ml-lg-4">
        <img src="https://kunshengsite.s3-ap-southeast-1.amazonaws.com/projects/android/world_logo_quiz/world-highscores.jpg" alt="world_logo_quiz_highscore" />
    </div>
</div>
Lastly, individual player performance and levels of completion are tracked per stage in a report card. They may also submit their scores onto a highscores leaderboards to see how well they fare against other players. Players who have solved the most number of logos using the fewest hints will be ranked higher, duh.

The highscore feature was added slightly later after World Logo Quiz was published onto the playstore. I think it definitely made the game more playable as the added element of competition added some flavour to an otherwise, mundane single player game. Post implementation of this feature saw some increase in daily downloads and usage rates and the highscore table is very well populated with all-time logo grandmasters of around the world.






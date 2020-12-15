---
layout: post
title: Slots Redux Game
date: 2020-12-11 12:00:00 -0600
description: Slots Redux by Jason Pape # Add post description (optional)
img: slots-redux.jpg # Add image post (optional)
fig-caption: A screenshot of Slots Redux # Add figcaption (optional)
tags: [Slots, Javascript, Tumult Hype, Games, Computer Science, jQuery, Halloween]
---

----
## Game
Click <a href="https://jasonkpape.github.io/slots-redux/" target="_blank">HERE</a> to play.

----
## Project Description
The final project for DGIM 2530 - Game Design 1, this is a modified version of my previous Slots game. The assignment was to alter the theme, add one improvement suggested by one of the playtesters of the previous version, and one new feature.

----
## Customization
Instead of creating a new theme from scratch&mdash;I spent considerable time creating the art, music, and sound effects for the previous version, and creating something of comparable quality would have required far more time than was available to me&mdash;I opted to recolor the existing art assets in order to give it the feeling of a palette swap.

One of the playtesters of the previous version had never played a slot machine before and found the whole process confusing. I added an optional tutorial scene.

The additional feature I implemented changes the behavior of the displays when the first and second displays land on the same symbol. In order to build anticipation, the third, still-spinning display is tinted blue. A timpani roll sounds, and the length of spin time is increased. If the third display lands on the same symbol as the first two, then a crash cymbal is heard, signifying that the player has landed a "big win." Since the timing of each round is no longer constant, I optimized the code so that the triggering of various sounds and functions occurs in the jQuery animate callback functions instead of through the use of the JavaScript setTimeout function.

----
## Hosting and Usability Testing
 A GitHub account was created and the game was hosted at <a href="https://jasonkpape.github.io/slots-redux/" target="_blank">https://jasonkpape.github.io/slots-redux/</a>. Students were then required to find two volunteers and have each perform a usability test. Students submitted the basic Tumult Hype file and the usability test results, along with a link to the actual game for grading.

----
[RETURN TO HOME](https://jasonkpape.github.io/jekyll-portfolio/)

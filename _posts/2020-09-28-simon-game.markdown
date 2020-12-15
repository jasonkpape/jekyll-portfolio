---
layout: post
title: Simon Game
date: 2020-09-28 12:00:00 -0600
description: Simon Says by Jason Pape # Add post description (optional)
img: simon.jpg # Add image post (optional)
fig-caption: A screenshot of Simon Says # Add figcaption (optional)
tags: [Simon, Javascript, Tumult Hype, Games, Computer Science]
---

----
## Game
Click <a href="https://jasonkpape.github.io/simonsays/" target="_blank">HERE</a> to play.

----
## Project Description
This is a recreation of the Simon electronic game originally sold by Milton Bradley. There are four buttons that light up and play a tone in a randomized order, and the player must reproduce the sequence, which gets longer with each round. An array of 100 entries is randomly generated at the beginning, and a separate array keeps track of how many entries in the sequence the user has remembered correctly so far.

----
## Customization
Students followed along with the instructor to create the base game and were then given two weeks to make the following modifications:

* Replace the title on the splash page and animate it
* Replace the original four button tones with new ones
* Modify the colors, images, and layout of the badge element that is displayed every five rounds
* Change the text and background colors, font families, and text positions

The following additional modifications were made:

* Added sound effect to the buttons on the splash screen
* Animated badge element
* Created new button spritesheets and other art elements with Adobe Illustrated
  * Imported as vector art
* Added title element in main scene that smoothly cycles through various colors
* Added a timer to keep track of how long the player has been playing
* Added code and extra scene to handle the (unlikely) case of the player making it through all 100 rounds
* Adjusted color scheme in an attempt at making the game colorblindness friendly (while avoiding original Simon colors)
* Added third 'turbo' mode
* Allowed user to choose from three different sound modes
  * Classic mode used recordings of the original Simon tones
  * Chord mode played piano chords
  * Animal mode played animal sound effects
* Added music to various scenes and events

All sound sound effects and music created with Propellerhead Reason, Adobe Audition, and ChipTone (https://sfbgames.com/chiptone/), except for the classic Simon tones, which I sourced from a video of someone playing the original game.

----
## Hosting and Usability Testing
A GitHub account was created and the game was hosted at <a href="https://jasonkpape.github.io/simonsays/" target="_blank">https://jasonkpape.github.io/simonsays/</a>. Students were then required to find two volunteers and have each perform a usability test. Students submitted the basic Tumult Hype file and the usability test results, along with a link to the actual game for grading.

----
[RETURN TO HOME](https://jasonkpape.github.io/jekyll-portfolio/)

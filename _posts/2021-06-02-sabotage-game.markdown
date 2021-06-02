---
layout: post
title: Saboteurs!
date: 2021-06-02 02:00:00 -0600
description: Saboteurs! by Jason Pape # Add post description (optional)
img: sabotage.jpg # Add image post (optional)
fig-caption: A screenshot of Saboteurs! # Add figcaption (optional)
tags: [Javascript, Tumult Hype, Games, Computer Science, Sabotage, Apple II, jQuery, Fixed Shooter]
---

----
## Project Description
This game is a recreation of the classic <cite>Sabotage</cite> computer game developed for the Apple II by Mark Allen and published On-Line Systems (which would later become Sierra On-Line). The player controls a rotating cannon and attempts to shoot passing crafts that attempt to drop parachuting robots to destroy the cannon. The goal is to shoot all of the invaders before they can descend upon the cannon. If four robots land on either side of the cannon, they will stack up against the cannon and destroy it causing the game to end.

----
## Game
Click <a href="https://jasonkpape.github.io/sabotage/" target="_blank">HERE</a> to play.

----
## Customization
Students followed along with the instructor to create the base game and were then were required to make the following modifications:

* Replace the flat cyan background with a background image
  * Used Adobe <cite>Photoshop</cite> to create a new image
* Modify the color, text, and layout of multiple elements within the splash, opening, or summary scenes
  * I made changes to all three scenes, including adding animated spritesheets of the enemy targets
* Replace at least three of the sound files in the base game
  * I created new sounds for all sound effects and added several more, using Reason Studios's <cite>Reason</cite>, <a href="https://sfbgames.itch.io/chiptone" target="_blank">SFB Games' <cite>ChipTone</cite></a>, and Adobe <cite>Audition</cite>.
* Modify the appearance of the choppers and paratroopers in the base game
  * I replaced the choppers with hovercraft and the paratroopers with robots
* Create a new version of the chopper-explosion or base-explosion spritesheets
  * I replaced both with spritesheets created in <cite>Photoshop</cite>, creating an animated spritesheet of the base melting instead of exploding

I made the following additional modifications:

* Added clouds to the background that animated to create a parallax effect
  * Divided remainder of the background to foreground and background layers
* Replaced the static hovercraft images with animated spritesheets
* Added animated spritesheets for when the hovercraft and robots are hit by projectiles and added code to animate them
* Wrote a new story for the opening scene
  * Replaced the original sounds with sounds of my own, including Morse code created with MorseCode.World's <cite><a href="https://morsecode.world/international/translator.html" target="_blank">Morse Code Translator</a></cite>
* Added the option for players to use 'steerable' projectiles: The paths of fired projectiles can be altered by rotating the cannon
* Added code to detect whether a projectile has struck a parachuting robot's body or parachute
  * If the parachute is struck, the robot falls, destroying any robot that has previously landed directly below it
* Added an animated (fictitious) company logo that displays when the game loads
* Refactored the jQuery code that animates the robot-stacking sequence to require only one function (instead of four), significantly reducing repeated code
  * Tweaked the speed and jumping animation of the robots
* Added touchscreen functionality, using touchscreen controls created in Adobe <cite>Illustrator</cite>
* Fixed various bugs in the base code
  * Fixed minor JavaScript array indexing error involving parachuting robots
  * Added code to allow player to restart a new game after the game is over
  * Created an array to keep track of which parachuting columns were in use so that multiple robots could not parachute down the same column at the same time (which caused unpredictable and sometimes game-breaking results)
* Fixed even more bugs introduced by myself while fixing the above
* Added code to allow the player to skip the logo, splash, and opening screens by pressing the spacebar
* Added code to make the hovercraft's begin falling as they explode
* Added music created with <cite>Reason</cite> and <cite>Audition</cite> to main and summary scenes
* Added an additional sequence when a game-over state is reached and the player is waiting for the currently parachuting robots to land
* Added a flickering-streetlight animation to the background
* Slightly increased the cannon rotation range to make it easier for players to shoot robots at the edges of the screen in time
* Added vector animation to represent robot spraying acid on the cannon during the game-over sequence

----
## Hosting and Usability Testing
 A GitHub account was created and the game was hosted at <a href="https://jasonkpape.github.io/sabotage/" target="_blank">https://jasonkpape.github.io/sabotage/</a> and linked on this portfolio page. Students submitted the basic Tumult Hype file along with a link to the actual game for grading.

----
[RETURN TO HOME](https://jasonkpape.github.io/jekyll-portfolio/)

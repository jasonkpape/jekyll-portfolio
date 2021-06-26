---
layout: post
title: Misadventure
date: 2021-06-26 17:00:00 -0600
description: Misadventure by Jason Pape # Add post description (optional)
img: adventure.jpg # Add image post (optional)
fig-caption: A screenshot of Misadventure # Add figcaption (optional)
tags: [Javascript, Tumult Hype, Games, Computer Science, Adventure, Atari 2600, Warren Robinett, easter egg, top-down]
---

----
## Project Description
<cite>Misadventure</cite> is a condensed recreation of the classic <cite>Adventure</cite> video game developed for the Atari 2600 by Warren Robinett. The game is played from a top-down view, and the player character can travel across over a dozen screens. The player can carry one item at a time, such as keys to open gates and a spear for defense against enemies. The goal of the game is to take the chalice in the black castle and place it inside the gold castle.

----
## Game
Click <a href="https://jasonkpape.github.io/adventure/" target="_blank">HERE</a> to play.

----
## Customization
Students followed along with the instructor to create the base game and were then were required to make the following modifications:

* Modify at least three scene backgrounds, using more vivid colors than those used in the original game
  * Used Adobe <cite>Photoshop</cite> to create new backgrounds for all game scenes
* Add some form of maze in one of three given scenes
  * Added a maze in one of the scenes and modified the layout of the other two scenes
* Modify at least three of the audio files
  * Replaced all sounds with sound effects created with Reason Studios <cite>Reason</cite> and Adobe <cite>Audition</cite>
* Change the dialogue of the wizard in the gold castle
  * Rewrote dialogue and created new animated wizard portrait with Adobe <cite>Illustrator</cite>
* Include your name in the credits scene and name playtests in the special-thanks section

I made the following additional modifications:

* Replaced the static dragon images with animated spritesheets
  * Dragons are now ducklike creatures in homage of the design of the original dragons
* Added a new scene to hold an important item
* Added 'typewriter' text animation to the dialogue boxes
* Added images that appear to illustrate the wizard's dialogue (and to help the player identify important items and enemies)
* Added animation to the splash scene
* Recorded a new video to play in the easter-egg room
  * Using techniques I learned about in last semester's film class, I recorded the video using my phone mounted on a tripod with a three-point lighting setup
  * Used Adobe <cite>Premiere Pro<cite> to edit and render the video
  * Recorded new audio track over the video and added subtitles
* Randomly positioned the easter-egg item in one of five scenes at the start of the game
* Modified how the player character and enemies interact to more closely reflect the original game.
  * When the enemies move close enough to the player, they switch to an attack pose. In 'easy' mode, the player has time to escape enemies' attacks
* Added an animated (fictitious) company-logo sequence that displays when the game loads
* Recorded music that plays throughout the game
  * Music fades seemlessly from one piece into another
  * A couple of music themes fade back in from where they left off when leaving and returning to their applicable areas
* Allowed users to progress or skip dialogue with keypresses in addition to 'next' buttons within the message boxes
* Removed all game-over states and implemented a 'reincarnation' system similar to that of the original game
  * When captured by an enemy, player is taken to a scene near the starting location
  * Any carried item is returned to its original location, except for the easter egg, whose location is again chosen randomly from among possible locations
  * All defeated enemies are revived
  * Game no longer ends after viewing easter-egg video
* Added a teleporter to the black castle as a shortcut
* Modified behavior of dropped items to prevent them from being dropped offscreen or within falls which can create dead-end states
* Added tutorial messages and other message boxes to describe to the player what is happening in the game
* Added alternate wizard dialogue that is triggered if the player returns with the chalice without having first been given the quest by the wizard
* Added a greater area on which the player can drop the chalice to place it on the table and win the game
  * The chalice now snaps into position in the center of the table
* Created new images for all items
* Added animation to credits scene

----
## Hosting and Usability Testing
 A GitHub account was created and the game was hosted at <a href="https://jasonkpape.github.io/aventure/" target="_blank">https://jasonkpape.github.io/adventure/</a>. Students were then required to find two volunteers and have each perform a usability test. Students submitted the basic Tumult Hype file along with a link to the actual game for grading.

----
[RETURN TO HOME](https://jasonkpape.github.io/jekyll-portfolio/)

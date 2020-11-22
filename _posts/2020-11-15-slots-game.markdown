---
layout: post
title: Slots Game
date: 2020-11-15 12:00:00 -0600
description: Slots by Jason Pape # Add post description (optional)
img: slots.jpg # Add image post (optional)
fig-caption: A screenshot of Slots # Add figcaption (optional)
tags: [Slots, Javascript, Tumult Hype, Games, Computer Science, jQuery, Halloween]
---

----
## Game
Click <a href="https://jasonkpape.github.io/slots/" target="_blank">HERE</a> to play.

----
## Project Description
This is an implementation of a slot machine. jQuery is used to control various buttons and animations. The code must randomize the results of each spin and check for winning combinations. Gameplay statistics are recorded and displayed to the player after they cash out.

----
## Customization
Students followed along with the instructor to create the base game and were then given two weeks to make the following modifications:

* Add a credits scene and include a button to bring the user back to the title scene
* Create a new game logo with new animation
* Create a specifc theme for the game
* Replace the spinning poker chips in the title scene with a newly created animation
* Replace the display strip images
* Modify the pay-table images to include the new display-strip images
* Change fonts, colors, and background images of buttons and other elements

I settled on a Halloween theme for my modified version of the game. I decided to change the currency from dollars to pieces of candy corn in the hope that it would make the game more agreeable to players who are not generally interested in gambling games. The bulk of my work on this game was spent creating new art in Adobe Illustrator, which I imported in vector format so as to decrease loading times and so that the art will continue to look crisp if the user magnifies their browser display. I replaced the spinning poker chip with a spinning candy corn.

I made the following additional modifications:

* Altered the flashing animation behind the displays when the player wins
* Created new art for the info and cash-out buttons
* Created new music and sound effects for when the player wins or tries to spin with insufficient funds
* Added music
* Modified code so that a result of three skulls halves the player's grand total
* Modified code to alter the chances of winning and losing
  * Displays landing between symbols more likely
  * Three of a kinds more likely
  * Three skulls more likely
* Added additional hidden easter-egg buttons
* Extended jQuery's animation easing so that spinning displays would slightly exceed their landing position before spinning back to it
* Additional sound effects created
* Replaced "Insufficient funds" alert with animated text

All the music and sound effects were created with Propellerhead Reason, GarageBand, and Adobe Audition. For the music that plays in the main scene, I felt like I needed to come up with something propulsive but not invasive and also long enough that it does not repeat too often during a single play session. I had aimed for a six-minute song, but due to time constraints, I was only able to come up with four minutes of music.

The 'back' easing formula I used was based on one used in jQuery Easing v1.3 (https://gsgd.co.uk/sandbox/jquery/easing/), which is open source under the BSD License.


----
## Hosting and Usability Testing
 A GitHub account was created and the game was hosted at <a href="https://jasonkpape.github.io/trivia/" target="_blank">https://jasonkpape.github.io/trivia/</a>. Students were then required to find two volunteers and have each perform a usability test. Students submitted the basic Tumult Hype file and the usability test results, along with a link to the actual game for grading.

----
[RETURN TO HOME](https://jasonkpape.github.io/jekyll-portfolio/)

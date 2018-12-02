Puzzler Project
===============

designed by Chikashi Miyama

 

Introduction
============

As a part of my coursework with Udacity, I created a simple mobile VR game,
called Puzzler. This game is a VR interpretation of [“Simon
says.”](https://en.wikipedia.org/wiki/Simon_Says) The player clicks 5 different
orbs in a dungeon room in the order that “Simon” shows. The player wins when she
or he can click all 5 orbs in the correct order.

The game is created with Unity and tested on Xiaomi RedMi Note 5 with a
google-cardboard-compatible headset.

 

Highlight
---------

The uniqueness of my puzzler is its UI. In VR, it is necessary to select the
most readable option but the selection of the font is also significantly
influence the mood and the atmosphere of the game. I selected three different
fonts for the UI and conducted some user tests in order to find a readable and
suitable font.

 

Outcomes
========

The following pictures are screenshots from the actual game. For more details
please read the “breakdown” section below and playback the videos.

 

 

the process
===========

Persona
-------

![](img/motokichi.PNG)

( [original image by
elmimmo](https://en.wikipedia.org/wiki/Ramen_shop#/media/File:Tachi-g%C3%BAi_ramen_2014_(14327023280).jpg)
- [CC BY 2.0](https://creativecommons.org/licenses/by/2.0/))

 

For the project, I created a user persona called Kenji. He is a young ramen-bar
chef and has almost no experience in VR, but watches Sci-Fi movies very often
with his friends in an IMAX-Theater nearby; he definitely has an interest in 3D
immersive experience. However, he is unmotivated to learn complicated rules in
general.

 

Sketches and Implementation
---------------------------

 

### UI Sketches

For designing the UI of the game, I made three different draft sketches and
selected the one without text except for “Puzzler” and “Congrats!” (The one on
the right) because the game may become more accessible to non-English speakers
like my persona, if I use less English words in the game.

![](img/sketches_processed.jpg)

 

### Implementing of the sketch in Unity

Based on the third draft, I made two icons with Inkscape, installed a font-type
font, and downloaded a free image of treasure. Using these materials, I
implemented two UI panels shown below.

 

![](img/implmentation.PNG)

 

User testing and iteration
==========================

 

### User experience

User testing

 

 

###  

 

 

Breakdown of final piece
========================

 

The entry point of the game, the player can start the game by clicking start
icon.

 

 

 

Dungeon room, where the player can play the actual game. Please pay attention to
the feed-forward and the feedback.

 

 

 

The end point of the game, where the player can restart the game by clicking the
rewind icon.

 

 

 

Next Step
=========

The Puzzler is a simple project but showcases essential building-blocks to
create an immersive VR experience. However, There are still rooms for
improvement. For example, the light from the torch is too static; a torch in a
real world emits more unstable light and some additional particle effects may
provide us with more convincing realism.

 

If you are interested in...
---------------------------

Please download the entire repository. Unity project and InkScape files (for UI
design), are available.

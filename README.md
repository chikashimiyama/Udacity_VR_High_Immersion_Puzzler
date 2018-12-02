Puzzler Project
===============

designed by Chikashi Miyama

![](img/entrance.PNG)

Introduction
============

As a part of my coursework with Udacity, I created a simple mobile VR game,
called Puzzler. This game is a VR interpretation of [“Simon
says.”](https://en.wikipedia.org/wiki/Simon_Says) The player clicks 5 different
orbs in a dungeon room in the order that “Simon” shows. The player wins when she
or he can click all 5 orbs in the correct order.

The game is created with Unity and tested on Xiaomi RedMi Note 5 with a
google-cardboard-compatible headset.

 

Outcomes
========

The following video depicts the experience of the actual game. For more details
please read the “breakdown” section below.

 

[Youtube Video](https://www.youtube.com/watch?v=IeFZDdO06eE)

![](https://img.youtube.com/vi/IeFZDdO06eE/0.jpg)

 

 

The process
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

 

### Icons design with Inkscape

For creating the oval-shaped panel and play/rewind icons, I used
[Inkscape](https://inkscape.org/), a free vector-graphic software.

 

![](img/inkscape.PNG)

 

### Implementing of the sketch in Unity

Based on the third draft, I made two icons with Inkscape, installed a font-type
font, and downloaded a free image of treasure. Using these materials, I
implemented two UI panels shown below.

 

![](img/implmentation.PNG)

After several iterations and based on feed-backs from the user, I decided to
make the panel transparent, so that the UI doesn’t disturbs the atmosphere of
the VR space. On the contrary, I used very vivid red color to emphasize the
button. At the end, I conducted a user test and confirmed that the function of
“play” and “rewind” button is understandable for her.

 

Scaling Issue
-------------

During the iteration, I realized the metal grid of the entrance is too close to
my head and it creates an unnatural feeling. At the end, I decided to scale up
the entire building significantly. I believe this correction creates a good
contrast between the foreground (the interactive orbs) and the background (the
building) and helps users to focus on the game content. The following
screenshots show the image of the dungeon room before and after the scale
correction.

 

![](img/before_after.png)

 

Breakdown of final piece
========================

 

The entry point of the game, the player can start the game by clicking “play”
icon.

![](img/start.PNG)

 

As soon as the player presses the start icon, she or he is transferred to this
dungeon room, where the player can play the actual “Simon says” game.

![](img/play.PNG)

 

The end point of the game, where the player can restart the game by clicking the
rewind icon.

![](img/end.PNG)

 

 

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

---
layout: essay
type: essay
title: Newtonium Release Notes
date: 2016-01-17
labels:
  - Unity
  - Piskel
  - Aseprite
---

## Newtonium
Welcome to my Release Notes page for Project Newtonium!  Newtonium is the working title of a physics learning game to be developed in Unity.  The target audience of this project is high school to college level students who are either interested in, or required to take an introductory pre-engineering physics course.  The goal of this project is to act as either a spark or a catalyst for interest in classical mechanics (applications of newton's laws and other topics) through the use of some traditional video game elements including a dialogue-driven story, animated graphics, and music.

<br/>
### *Latest Update: February 15, 2017*
I completed the walk cycle animation and imported it into Unity.  I wrote a simple script to control the protagonist (who I will refer to as "Main" from this point on as his working name).  At the moment the script simply supports left and right movement, while the walk animation is not coordinated to only activate while Main is standing still.  I will fix this for the next update, as well as fix the animation to "flip" depending on if the player is moving left or right.  I created a simple floor graphic with collision detection, which is demonstrated above as Main walks off a cliff, but this is more of a demo and not indicative of where the actual gameplay is headed.  I created some additional graphics as well, which can be seen for now in my sprites folder, but upon my meeting with my project advisor I will be focusing mostly on scripts to structure player and game behavior, and trying to incorporate new graphics simply as needed and for functional purposes rather than going straight for a "finished product look".
<br/>

#### *February 1, 2017*
<br/>
<div class="ui small rounded images">
  <img class="ui image" src="../images/newtonia_roughWalk.gif">
</div>
I have nearly completed the walk cycle animation for the protagonist of the game.  I wanted to be finished with this task by now, I think that my OCD tendencies with visual stuff is getting the better of me here, but I believe this task will be completed within a week, and the controllable sprite animation will be imported into a very basic test stage (simply the character on a plain background that can be controlled).  Not coincidentally, there is a meeting scheduled with our instructor and advisor for this independent study project in a week's time, and thus I am shooting for the above and more to be posted here for the next relase notes update.
<br/>

#### *January 16, 2017*
<br/>
One week into a 15-week period of time allotted to this project, the focus has been largely on the planning of how to best use the remaining 14 weeks towards completion of the project.  I have skimmed through a number of courses on [Udemy](https://www.udemy.com/courses/) and YouTube that feature Unity development related to this project, and while it appears that I cannot yet accurately finalize which courses will be the best to focus on, I am fairly confident that [this course](https://www.udemy.com/unity2dplatformer/) and [this video series](https://www.youtube.com/results?search_query=unity+rpg+tutorial+gamesplusjames) will teach me techniques that I can use in a similar fashion for the implementation of my game.  Specifically, the animation and manipulation of 2D sprite-based characters for the first series, and the use of dialogue boxes involving multiple characters from the second instructional video set.

*Storyboards*
<br/>
<div class="ui large rounded images">
  <img class="ui image" src="../images/releaseNotes_sB01.JPG">
  <img class="ui image" src="../images/releaseNotes_sB02.JPG">
  <img class="ui image" src="../images/releaseNotes_sB03.JPG">
</div>
Pictured above are storyboards for the introduction to the game.  Eventually I would like to have a title screen and possibly an additional introductory screen or two, but this is the main part of the introduction of our main character and the story he partakes in that motivates the solving of physics problems.  The working plot summary is that Main, our protagonist, lives in a fictional universe where he is part of a military academy.  Immediately the military base he occupies is under attack, and he is introduced to the first of many situations where he must use physics to get through his dilemma.  The idea for the story following this introductory level, is that Main's world will have been changed drastically following this sudden outbreak of war, and the new world is ravaged and full of people in need and being oppressed by the militia that remains after the fallout.  Main and his sidekick Cascopter decide that they will not harm anyone in this new world, and will instead use their abilities with physics to save as many people as they can.

### Goals for the next month:
After getting basic behavior for my existing Main character and CAScopter (basically will be following Main like a fairy/UFO dog), I need to get dialogue boxes into the game, which will be the basis for both communicating the story and instructing players on how to play the game.  I want to get a simple dialogue-based problem in the game, while also starting on the structure for the presentation of the actual level/problem presentation, with rough shapes/very quickly done graphics acting as fill-ins for what will later be finalized game graphics.

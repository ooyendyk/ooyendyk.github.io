---
layout: project
type: project
image: images/mlART1.jpeg
title: Atavistic-Dreams
permalink: projects/atavistic-dreams
# All dates must be YYYY-MM-DD format!
date: 2020-03-21
labels:
  - Python
  - ML
  - AI
  - Keras
  - Tensorflow
summary: Atavistic-Dreams, is a project to generate art through the use of machine learning.
projecturl: https://ooyendyk.github.io/projects/atavistic-dreams
---


<video width="300" height="300" controls><source src="../images/mlART0.mp4" type="video/mlART0.mp4"></video>
<img class="ui medium center floated rounded image" src="../images/mlART1.jpeg">
<img class="ui medium right floated rounded image" src="../images/mlART2.jpeg">
<img class="ui medium left floated rounded image" src="../images/mlART3.jpeg">
<img class="ui medium center floated rounded image" src="../images/mlART4.jpeg">
<img class="ui medium right floated rounded image" src="../images/mlART5.jpeg">
<br />
<br />

<p>After stumbling across some classic art/design magazines, I started toying with the idea of taking up digital art.</p>

There was one problem with taking up a new hobby; I simply didn't have the time to learn a new skill.

Being a programmer, I decided to go for the obvious solution; automate it.

I decided to use machine learning, beacuse then I'd be almost completely removed from the artistic procces.

This is ideal, because then I'd have to exert no effort in coming up with the meaning behind the art.

I started out by scraping digital art from instagram. This dataset was then fed into styleGAN, and trained for 2000 epochs.

The resulting model was used to generate images, which were then pased to another ML algorithim,
SRCNN to upscale the images from 1042x1042 to 4096x4096.


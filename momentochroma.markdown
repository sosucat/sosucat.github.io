---
layout: page
title:  "MomentoChroma"
permalink: /momentochroma/
google_analytics: UA-NNNNNNNN-N
---

<p style="font-size: 14px;font-weight:400;line-height:1.8">
  Photography is a medium that cuts out and fixes a moment in flowing time, and its realism presents its image in a compelling way.
  The fixation of the moment removes from the photographic medium the ephemeral reality that we, who live in the flow of time, usually perceive.
  The persuasiveness of the photograph also strongly presents the inaccurate colors of AI colorization.
  MomentoChroma makes us, whose gaze scans space in time, perceive colorful images only while we do not move our gaze in order to vividly realize the reality of the past.
  It is a perceptual experience clothed in aura, and the momentary color becomes a catalyst for evoking the colors of people's memories.
  As our peripheral vision is limited in spatial resolution, the AI-generated colors convey the overall atmosphere instead of convincing the viewers.
</p>


Keep staring at the dot at the center of the inverted color image. And you can experience a momental colorization of the black-and-white image.

<p>
  <img src="/assets/images/momentochroma/momentochroma_moga.gif" alt="momentochroma_demo_moga" style="width: 100%;">
  <br>
  
  Original photograph: Kyoyo Kagayama. 1928. Young moga (modern girls) walk down a Ginza street in 1928 dressed in 'Beach Pyjama Style.'
</p>
<br>

The development of GAN (Generative Adversarial Network) has made it possible to achieve AI colorization of old black-and-white photographs with some accuracy.
This is a fantastic technology that adds a sense of realism to memories that until now could only be seen in black and white, as if they were being experienced now.
However, there are two areas for improvement.
<br>
The first is the loss of the reality of ephemerality as the photograph cuts out time and presents it forever.
While the photograph makes it possible to observe the moment it cuts out, it loses the ephemerality, earnestness and aura that derives from the implicit understanding that the scene can only exist at that moment.
For example, the facial expression of the person in front of us, which changes from moment to moment and which we can no longer experience in the next moment, causes us to cherish what is in front of us and what has passed as a memory.
However, in a photograph, the same facial expression is fixed for a long time, so there is no such "affection for the moment".
<br>
The second is the inaccuracy of AI colorization.
This is due to both technical and perceptual factors.
Technical factors include the low resolution and high noise content of older photographs, as well as the fact that photographs often contain objects that are not present in modern training data.
Perceptual factors include the difference between the visual environment at the time the photograph was taken and that of the person viewing the photograph, and the fact that the colors in the memory do not always match the "physically accurate" colors.
As photograph presents its image in a persuasive manner, the inaccurate colorization could overwrite people's memories.

Regarding this inaccuracy of AI colorization, <a href="https://doi.org/10.1145/3354918.3361904" style="color:inherit; text-decoration:underline">Niwata & Watanave</a> offer an interesting solution.
They showed AI-colorized photos to the people involved in the shoot and manually corrected the colors as they conversed about their memories of the time.
This is a good example of human-AI collaboration in which the person has agency, i.e., the AI generates the colored photos as a trigger and aid to the people's interaction and memory, rather than presenting them to the people as the truth.

I created MomentoChroma as a medium to perform such human correction of AI colorization on a cognitive level, and to overcome the characteristics of photography that do not have the sense of reality caused by ephemerality.
In MomentoChroma, people feel colors through a visual illusion called <a href="https://doi.org/10.1038/1961143a0" style="color:inherit; text-decoration:underline">afterimage illusion</a>.
When the human eyes view a colored surface for some time and a blank surface is presented afterwards, they perceive the afterimage in the complementary colors for a while as long as the eyes do not move.
MomentoChroma makes us, whose gaze scans space in time, perceive colorful images only while we do not move our gaze in order to vividly realize the reality of the past.
It is a perceptual experience with aura, and the momentary color becomes a catalyst for evoking the colors of people's memories.
As our peripheral vision is limited in spatial resolution, the AI-generated colors convey the overall atmosphere instead of convincing the viewers.
<br>

<p>
  <img src="/assets/images/momentochroma/momentochroma_process.jpg" alt="momentochroma_process" style="width: 100%;">
  <br>
  The process of making MomentoChroma. The colorized photo is generated by the GAN, such as <a href="https://github.com/jantic/DeOldify#nogan-based-deoldify-model" style="color:inherit; text-decoration:underline">NoGAN-Based DeOldify Model</a> or <a href="https://deepai.org/machine-learning-model/colorizer" style="color:inherit; text-decoration:underline">DeepAI Image Colorization</a>.
  Then, the generated colored image is inverted, and a dot is put at the center (you can use any image editing program/software/<a href="https://pinetools.com/invert-image-colors" style="color:inherit; text-decoration:underline">online service</a>).
  Finally, the MomentoChroma gif file consisting of the inverted image (12 sec) and the original black-and-white image (6 sec) is created (you can use any program/software/<a href="https://ezgif.com/maker" style="color:inherit; text-decoration:underline">online service</a>).
</p>

<br><br>

<p>
  <img src="/assets/images/momentochroma/momentochroma_kyoto.gif" alt="momentochroma_demo_kyoto" style="width: 100%;">
  <br>
  Original photograph: A group of Maiko girls on a balcony overlooking the Kamo River in Kyoto, around late 1910s.
</p>

<br><br>

<p>
  <img src="/assets/images/momentochroma/momentochroma_paris.gif" alt="momentochroma_demo_paris" style="width: 100%;">
  <br>
  Original photograph: G. Agié. 1910. Les Créateurs de la Mode. Charles Eggimann Editeur, Paris.
</p>

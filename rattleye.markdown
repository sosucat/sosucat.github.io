---
layout: page
title:  "RattlEye"
permalink: /rattleye/
google_analytics: UA-NNNNNNNN-N
---

<br>

<p style="font-size: 12px;font-weight:300">
  <img src="/assets/images/rattleye/rattleye_overview.jpg" alt="rattleye_overview" style="width: 100%;" class="center">
  <br>
  RattlEye demonstrated at SIGGRAPH 2022. Gaze-based thermal feedback enables vision-like thermal experience.
</p>
<br>

<p style="font-size: 16px;font-weight:450;letter-spacing:0.0px;line-height:2.5">
  RattlEye is a new media experience where people feel thermal sensation according to their gaze.
  Just like you perceive visible lights according to your gaze in vision, you can perceive infrared rays (thermal sensation) according to your gaze in RattlEye.
  You can "see" the world through your skin.
  People often react like, "Wow! It works!"
</p>
<br>

<h2>CONCEPT</h2>
<p style="font-size: 12px;font-weight:300">
  <img src="/assets/images/rattleye/rattleye_description.jpg" alt="rattleye_description" style="width: 100%;" class="center">
  <br>
  When the person sees the sun, they feel warmth. When they see the ocean, they feel coolness.
</p>
<br>

<p style="font-size: 14px;font-weight:400">
  Infrared ray, along with visible light, is emitted from the sun and thermal light sources and is reflected by the world to reach us.
  Therefore, in perceiving the world, we not only see visible light with our eyes, but also feel infrared (heat) with our skin.
  The importance of heat in perceiving the world is highlighted by the fact that <a style="color: inherit; text-decoration: underline;" href="https://www.jstor.org/stable/24966551">rattle snakes see the world through both visible and infrared lights</a>.
  However, thermal sensation has a lower spatial resolution than vision, and it also does not have the same immediate effect on our attention, consciousness, and perceptual world as vision does.
  I thought that the strong connection of vision to attention, consciousness, and the perceptual world is due to the fact that vision is perceived at high refresh rate in response to the gaze, something that is constantly interacting with attention, consciousness, and the perceptual world.
  I also considered that spatial scanning by gaze converts the fast refresh of the limited perceptual unit of central vision into spatial perception.
  (As an aside, Richard A. Bolt's <a style="color: inherit; text-decoration: underline;" href="https://doi.org/10.1145/965161.806796">Gaze-Orchestrated Dynamic Windows</a> seems to have applied similar ideas to the interface.)
  Therefore, to transform thermal sensation into vision-like sensation, we developed the RattlEye, which provides high refresh rate thermal feedback according to eye gaze.
</p>
<br>

<h2>IMPLEMENTATION</h2>
<p style="font-size: 12px;font-weight:300">
  <img src="/assets/images/rattleye/rattleye_side.jpg" alt="rattleye_side" style="width: 100%;" class="center">
  <br>
  RattlEye consists of an eye tracker, a visual display (a monitor in this case), a shutter mechanism, and an infrared source.
  The amount of infrared (heat) provided to the person is calculated based on their gaze position on the visual display.
  The angle and the shutter mechanism is controlled so that the required amount of infrared is passing through it.
  The relationship between the gaze and heat is defined differently for different contents.
  For the demonstration at SIGGRAPH 2022, the amount of heat was predefined for each pixel / object of the images (e.g., the sun is the hottest, while the ocean is the coolest).
</p>
<br>

<h2>VIDEO</h2>
<p class="videoWrapper">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/KbPBmUG0smU?si=jIzNiQS0PiCVh79u" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>
<br>

<h2>DEMOS</h2>
SIGGRAPH 2022 Emerging Technologies.
<br>
<p style="font-size: 12px;font-weight:300">
  <img src="/assets/images/rattleye/rattleye_installation1.jpg" alt="rattleye_installation1" style="width: 100%;" class="center">
  <br>
  Demo at SIGGRAPH 2022.
</p>

<br><br>

<p style="font-size: 12px;font-weight:300">
  <img src="/assets/images/rattleye/rattleye_group.jpg" alt="rattleye_group" style="width: 100%;" class="center">
  <br>
  Demo at SIGGRAPH 2022.
</p>

<h2>PUBLICATIONS</h2>
<ol style="font-size:14px; font-weight:320">
<li><p><strong>Sosuke Ichihashi</strong>, Arata Horie, Masaharu Hirose, Zendai Kashino, Shigeo Yoshida, Sohei Wakisaka, and Masahiko Inami.
ThermoBlinds: Non-Contact, Highly Responsive Thermal Feedback for Thermal Interaction.
In Special Interest Group on Computer Graphics and Interactive Techniques Conference Emerging Technologies (SIGGRAPH ’22 Emerging Technologies ). 2022.
<a style="color: inherit; text-decoration: underline;" href="https://doi.org/10.1145/3532721.3535569">doi</a></p>
</li>
<li><strong>Sosuke Ichihashi</strong>, Arata Horie, Masaharu Hirose, Zendai Kashino, Shigeo Yoshida, and Masahiko Inami.
High-Speed Non-Contact Thermal Display Using Infrared Rays and Shutter Mechanism.
In Adjunct Proceedings of the 2021 ACM International Joint Conference on Pervasive and Ubiquitous Computing and Proceedings of the 2021 ACM International Symposium on Wearable Computers (UbiComp-ISWC ’21 Adjunct). 2021.
<b style="color:blue;">Best Paper Award</b>.
<a style="color: inherit; text-decoration: underline;" href="https://doi.org/10.1145/3460418.3480160">doi</a>
</li>
</ol>
<br>

<h2>AWARDS</h2>
MIMSVAI Best Paper Award. 2021. UbiComp-ISWS 2021 Adjunct.

<h2>CREDITS</h2>
Sosuke Ichihashi<br>
Arata Horie<br>
Masaharu Hirose<br>
Zendai Kashino<br>
Shigeo Yoshida<br>
Sohei Wakisaka<br>
Masahiko Inami<br>
Tomoya Sasaki<br>

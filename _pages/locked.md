---
permalink: /locked
title: "Locked in"
layout: splash
author_profile: false
---

<br>

In this environment, agents need to collaborate to make a soup containing an onion and a tomato within 7 timesteps. However, the recipe requires placing the onion into the pot precisely one timestep after the tomato to get +1 reward, or the soup will be ruined, giveing a reward of 0. The agents' action space be composed of the following: rotate left, rotate right, and interact. 

This environment has two strategic equivalence classes: one class has the left agent collecting an onion and the right agent collecting a tomato, while the other class has the roles switched. 

{% include locked_slider.html %}

---
permalink: /schelling
title: "Schelling point"
layout: splash
author_profile: false
---

<br>

Agents get a reward of +1 for each onion that is put into either of the pots. Agents can move left, right, up, down, stay still, and "interact" to pick up or place vegetables. We use a horizon of 8. In this environment agents need to coordinate on who gets to occupy the useful central tile without running into each other (which results in a no-op). Optimal policies achieve a total reward of +2.  

This environment has only two equivalence classes, depending on which agent gets to occupy the central square first.  After one agent occupies the central square, the symmetry in the problem is broken and the second agent’s best responses become fixed.

 {% include schelling_slider.html %}

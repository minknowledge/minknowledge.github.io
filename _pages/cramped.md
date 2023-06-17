---
permalink: /cramped
title: "Cramped"
layout: splash
author_profile: false
---

<br>

Agents get a reward of +1 for each onion that is put into the pot within a horizon of 9. Agents can move left, right, up, down, stay still, and "interact" to pick up or place vegetables. In this environment agents need to coordinate on who gets to occupy the useful central tile without running into each other (which results in a no-op). Optimal policies achieve a total reward of +2.  

This environment has only two strategic equivalence classes, depending on which agent gets to collect the onions first.

{% include cramped_slider.html %}

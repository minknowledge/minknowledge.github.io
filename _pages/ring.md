---
permalink: /ring
title: "Coordination Ring"
layout: splash
author_profile: false
---

<br>

Agents get a reward of +1 by placing an onion and a tomato into the same pot within a horizon of 11. Agents can move left, right, up, down, stay still, and "interact" to pick up or place vegetables.

At first examination, one might predict that there should
be multiple strategic equivalence classes in this problem, perhaps resulting from
which agent gets which vegetable, which pot to use, or the
various options for how the agents could walk around the
central island to stay out of each other’s way. However, this environment has only a single strategic equivalence class containing
all of these variations!
Conceptually, this means that both agents do
not need to know anything about their partner's policy in order to
play optimally; agents require no preexisting agreements on
how to successfully coordinate in the environment.

{% include ring_slider.html %}

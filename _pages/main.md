---
permalink: /
title: "Who Needs to Know? Minimal Knowledge for Optimal Coordination"
layout: splash
author_profile: false
header:
  overlay_color: "#808080"
  overlay_filter: "0.5"
  actions:
    - label: <i class="fas fa-fw fa-file-pdf"></i> Paper
      url: "/assets/pdfs/paper.pdf"
    # - label: <i class="fab fa-fw fa-github"></i> Code
    #   url: "/assets/pdfs/paper.pdf"
excerpt: <font size="5"> Niklas Lauffer, Ameesh Shah, Micah Carroll, Michael Dennis, Stuart Russell </font>
intro: 
  - excerpt: "Some words here describing the project."
feature_main:
  - image_path: /assets/images/br_viz.png
    alt: "Visualization of how the SER is obtained from the best-response map"
    title: "Schelling Point"
    excerpt: "The cooks need to coordinate on who gets to occupy the useful central tile to deposit two onions within the time limit."
feature_row1:
  - image_path: /assets/images/overcooked_schelling.png
    alt: "Schelling point Overcooked layout"
    title: "Schelling Point"
    excerpt: "The cooks need to coordinate on who gets to occupy the useful central tile to deposit two onions within the time limit."
    url: "/schelling"
    btn_label: "More details"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/overcooked_ring.png
    alt: "Coordination ring Overcooked layout"
    title: "Coordination Ring"
    excerpt: "The cooks need to deposite an onion and a tomato into the same pot. The cooks cannot occupy the same spot, requiring them to coordinate on how they pass around the central island."
    url: "/ring"
    btn_label: "More details"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/overcooked_cramped.png
    alt: "Cramped room Overcooked layout"
    title: "Cramped Room"
    excerpt: "The cooks need to coordinate on low-level movements to avoid getting in each other's way in order to get two onions into the pot within the time limit."
    url: "/cramped"
    btn_label: "More details"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/overcooked_tiny.png
    alt: "Locked in Overcooked layout"
    title: "Locked In"
    excerpt: "Cooks need to coordinate on the timing of a recipe involving onions and tomatoes using a single pot. Includes a fully- and partially-observed version."
    url: "/locked"
    btn_label: "More details"
    btn_class: "btn--primary"
---

Successful coordination in multiagent settings often requires knowing relevant details about your partners’ strategies. Safely driving on the road requires knowing that other drivers will driving on the right side of the road, stop on red and go on green, and alternate at stop signs.
However, there are often many more irrelevant details that you don’t need to know: other drivers' low-level motor controls, what their destinations are, or what type of music they like to listen to.

In this research project, we explore and formalize the idea that in multiagent settings there are **strategically relevant** and **strategically irrelevant** pieces of knowledge about other player’s strategies, but only the relevant aspects are necessary for optimal coordination.


{% include figure image_path="assets/images/br_viz.png" alt="Visualization of how the SER is obtained from the best-response map" %}

We introduce the idea of a **strategic equivalence relation (SER)**: strategies (on the left) are equivalent if they induce the same best response (on the right) from the other player. SERs naturally partition the strategy space (left) into different conventions for solving the game. Below you can find links to visualizations of the SERs for the strategies in various *Overcooked* environments.


{% include feature_row id="feature_row1" type="left" %}
{% include feature_row id="feature_row2" type="left" %}
{% include feature_row id="feature_row3" type="left" %}
{% include feature_row id="feature_row4" type="left" %}

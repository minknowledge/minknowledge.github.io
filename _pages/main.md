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
    excerpt: "Cooks need to coordinate on the timing of a recipe involving onions and tomatoes using a single pot. Includes a fully and partially-observed version."
    url: "/locked"
    btn_label: "More details"
    btn_class: "btn--primary"
---


{% include feature_row id="feature_row1" type="left" %}
{% include feature_row id="feature_row2" type="left" %}
{% include feature_row id="feature_row3" type="left" %}
{% include feature_row id="feature_row4" type="left" %}

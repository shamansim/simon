---
title: "Portfolio: Portraits"
layout: splash
permalink: /portraits/
date: 2018-11-01T20:30:41+02:00
header:
  overlay_image: /assets/images/splash-photography.jpg
  overlay_filter: 0.5
  cta_label: "Visit my Instagram account"
  cta_url: "https://www.instagram.com/shamansim/"
  caption: "All rights reserved"
sidebar:
  nav: "photography"
modified: 2018-11-01T20:42:00
feature_row:
  - image_path: assets/images/SimonBessonGirard-Calm.png
    alt: "Calm"
    title: "Calm"
  - image_path: /assets/images/SimonBessonGirard-Connection.png
    alt: "Connection"
    title: "Connection"
  - image_path: /assets/images/SimonBessonGirard-IceCream.png
    alt: "Ice cream"
    title: "Ice cream"
feature_row2:
  - image_path: /assets/images/biology-phd.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/biology-phd.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/biology-phd.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}

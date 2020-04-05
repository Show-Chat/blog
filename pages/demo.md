---
layout: page
sidebar: right
title: "Demo"
meta_title: "Demo test page"
permalink: "/demo/"
image_sliders:
  - slider1
  - slider2
  - slider3
---

{% include slider.html selector="slider1" %}

## slider 2

same images, different settings.

{% include slider.html selector="slider2" %}

## slider 3

same images, minimal settings, no bullets, no captions, no navigation

{% include slider.html selector="slider3" %}

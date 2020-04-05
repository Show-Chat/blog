---
layout: page
header:
  image_fullwidth: costiui2020.jpg
sidebar: right
meta_title: "Demo test page"
permalink: "/demo2/"
image_sliders:
  - slider1
  - slider2
  - slider3
---

{% include slider.html selector="slider1" %}

helo

<div class="row t60">
    <div class="medium-6 columns b30">
        <img src="{{ site.urlimg }}webdesign_screenshot_nixdorf.jpg" alt="">
        <p> Website: Nixdorf Internatsberatung &amp; Schulberatung</p>
    </div><!-- /.medium-6.columns -->

    <div class="medium-6 columns b30">
        <img src="{{ site.urlimg }}webdesign_screenshot_jcorneille.jpg" alt="">
        <p>Website: <a href="http://jcorneille.de">Grafik Design Jeannette Corneille</a></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->

{% include alert info='Filmari cu drona Costiui' %}

<div class="flex-video">
        <iframe width="420" height="315" src="//www.youtube.com/embed/PuP1-7USgDI" frameborder="0" allowfullscreen></iframe>
</div>

{% include alert warning='This is a warning.' %}
{% include alert info='An info box.' %}
{% include alert success='Yeah, you made it!' %}
{% include alert alert='Danger!' %}
{% include alert terminal='jekyll -serve' %}
{% include alert text='Just a note!' %}

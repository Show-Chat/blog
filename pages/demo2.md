---
layout: page
sidebar: right
meta_title: "Demo test page"
permalink: "/demo2"
image_sliders:
  - slider1
  - slider2
  - slider3
---

{% include slider.html selector="slider1" %}


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

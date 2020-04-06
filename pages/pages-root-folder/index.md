---
layout: page
header:
  image_fullwidth: costiui2020.jpg
sidebar: right

image_sliders:
  - slider1
  - slider2
  - slider3
permalink: /index.html 
homepage: true 
---
{% include slider.html selector="slider1" %}

{% include alert info='Filmari cu drona Costiui' %}

{% include video_costiui.html %}

<div class="row t60">
    <div class="medium-6 columns b30">
        <img src="{{ site.urlimg }}ronaszek-kep.jpg" alt="">
        <p> Website: Nixdorf Internatsberatung &amp; Schulberatung</p>
    </div><!-- /.medium-6.columns -->

    <div class="medium-6 columns b30">
        <img src="{{ site.urlimg }}ronaszek-tajkep.jpg" alt="">
        <p>Website: <a href="http://jcorneille.de">Grafik Design Jeannette Corneille</a></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->

{% include alert info='Ultimul Articol' %}
{% include newpost.html %}


{% include alert info='Facebook Coment' %}
<div class="fb-comments" data-href="https://www.facebook.com/CostiuiNet" data-width="" data-numposts="5"></div>

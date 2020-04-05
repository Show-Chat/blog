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

{% include alert alert='Coștiui este un sat în comuna Rona de Sus din judeţul Maramureş, Transilvania, România.' %}
{% include alert info='Coștiui (în maghiară Rónaszék și în ucraineană Коштіль) este un sat în comuna Rona de Sus din județul Maramureș, Transilvania, România.' %}
{% include alert info='Satul Costiui este situat în nordul României, în Depresiunea Maramuresului, fiind marginit de localitatea Bârsana în Sud, localitatea Valea Stejarului în Sud-Vest, localitatea Petrova în Est si localitatea Rona de Sus în Vest.' %}
{% include alert info='Satul Costiui se situeaza pe DN186A, la o distanta de 20 de km de municipiul Sighetu Marmatiei, 47 de km de orasul Viseu de Sus si 80 de km de municipiul Baia Mare.' %}

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


{% include video_costiui.html %}


{% include alert info='Coștiui (în maghiară Rónaszék și în ucraineană Коштіль) este un sat în comuna Rona de Sus din județul Maramureș, Transilvania, România.<p>Satul Costiui este situat în nordul României, în Depresiunea Maramuresului, fiind marginit de localitatea Bârsana în Sud, localitatea Valea Stejarului în Sud-Vest, localitatea Petrova în Est si localitatea Rona de Sus în Vest.</p>
Satul Costiui se situeaza pe DN186A, la o distanta de 20 de km de municipiul Sighetu Marmatiei, 47 de km de orasul Viseu de Sus si 80 de km de municipiul Baia Mare.' %}

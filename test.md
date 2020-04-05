---
layout: index
sidebar: right
meta_title: "Test page"
permalink: "/test/"
image_sliders:
  - slider1
  - slider2
  - slider3

widget1:
  title: "Blog & Portfolio"
  url: 'https://phlow.github.io/feeling-responsive/blog/'
  image: widget-1-302x182.jpg
  text: 'Every good portfolio website has a blog with fresh news, thoughts and develop&shy;ments of your activities. <em>Feeling Responsive</em> offers you a fully functional blog with an archive page to give readers a quick overview of all your posts.'
widget2:
  title: "Why use this theme?"
  url: 'https://phlow.github.io/feeling-responsive/info/'
  text: '<em>Feeling Responsive</em> is heavily customizable.<br/>1. Language-Support :)<br/>2. Optimized for speed and it&#39;s responsive.<br/>3. Built on <a href="https://foundation.zurb.com/">Foundation Framework</a>.<br/>4. Seven different Headers.<br/>5. Customizable navigation, footer,...'
  video: '<a href="#" data-reveal-id="videoModal"><img src="https://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Download Theme"
  url: 'https://github.com/Phlow/feeling-responsive'
  image: widget-github-303x182.jpg
  text: '<em>Feeling Responsive</em> is free and licensed under a MIT License. Make it your own and start building. Grab the <a href="https://github.com/Phlow/feeling-responsive/tree/bare-bones-version">Bare-Bones-Version</a> for a fresh start or learn how to use it with the <a href="https://github.com/Phlow/feeling-responsive/tree/gh-pages">education-version</a> with sample posts and images. Then tell me via Twitter <a href="https://twitter.com/phlow">@phlow</a>.'

---




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


<div class="row t30">
    <div class="medium-4 columns">
        <img src="{{ site.urlimg }}webdesign_screenshot_stilwandel.jpg" alt="">
        <p>Website: <a href="http://stilwandel-koeln.de">Stilwandel-Koeln.de</a></p>
    </div><!-- /.medium-4.columns -->

    <div class="medium-4 columns">
        <img src="{{ site.urlimg }}webdesign_screenshot_tarnkappe.jpg" alt="">
        <p>Website: <a href="http://tarnkarppe.info">Tarnkappe.info</a></p>
    </div><!-- /.medium-4.columns -->

    <div class="medium-4 columns">
        <img src="{{ site.urlimg }}webdesign_screenshot_schriefer.jpg" alt="">
        <p>Website: <a href="http://www.psychotherapie-schriefer.de/">Praxis für psychologische Psychotherapie Simone Schriefer</a></p>
    </div><!-- /.medium-4.columns -->
</div><!-- /.row -->







{% include slider.html selector="slider1" %}

## slider 2

same images, different settings.

{% include slider.html selector="slider2" %}

## slider 3

same images, minimal settings, no bullets, no captions, no navigation

{% include slider.html selector="slider3" %}

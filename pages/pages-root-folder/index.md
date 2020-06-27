---
layout: page
header:
  image_fullwidth: showchat.png
sidebar: right

image_sliders:
  - slider1
  - slider2
  - slider3
permalink: /index.html 
homepage: true 
---

{% include webchat.html %}

{% include radio2.html.html %}

{% include alert info='ShowChat Romania' %}

<div class="row t60">
    <div class="medium-6 columns b30">
    <a href="/test1">
<img src="{{ site.urlimg }}test1.jpg"  alt="test1"></a>
	    <div align="center">test1</div>
	    <a class="button tiny radius" href="https://api.showchat.tk/radio/images/no-cover-large.gif">{{ site.data.language.read2 }}</a>
    </div><!-- /.medium-6.columns -->

    <div class="medium-6 columns b30">
    <a href="/test2">
        <img src="{{ site.urlimg }}test2.jpg" alt="test2"></a>
       <div align="center">test2</div>
	<a class="button tiny radius" href="test2">{{ site.data.language.read2 }}</a>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->


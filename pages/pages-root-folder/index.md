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
<img src="{{ site.urlimg }}castel-apaffi-costiui.jpg"  alt="monument istoric castelul apaffi">
        <a href="https://blog.costiui.net/monument-istoric/castelul-apaffi/">Castelul Apaffi</a>
    </div><!-- /.medium-6.columns -->

    <div class="medium-6 columns b30">
        <img src="{{ site.urlimg }}ronaszek-tajkep.jpg" alt="">
        <a href="https://blog.costiui.net/video/filmari-cu-drona/">Filmare cu drona Costiui</a>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->

{% include alert info='Ultimul Articol' %}
{% include newpost.html %}


{% include alert info='Facebook Coment' %}
<div class="fb-comments" data-href="https://www.facebook.com/CostiuiNet" data-width="" data-numposts="5"></div>

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
<div class="medium-4 columns frontpage-widget">
	{% if include.widget.video %}
		{{ include.widget.video }}
	{% elsif widget_url == empty %}
		{% if widget_image != empty %}<img src="{{ widget_image }}" alt="" />{% endif %}
	{% else %}
		<a href="{{ widget_url }}">
			{% if widget_image != empty %}<img src="{{ widget_image }}" alt="" />{% endif %}
		</a>
	{% endif %}
	<h2 class="font-size-h3 t10">{{ include.widget.title }}</h2>

	{% if include.widget.text != empty %}<p>{{ include.widget.text }}</p>{% endif %}
	{% if widget_url != empty %}<p><a class="button tiny radius" href="{{ widget_url }}">{{ site.data.language.more }}</a></p>{% endif %}
</div>

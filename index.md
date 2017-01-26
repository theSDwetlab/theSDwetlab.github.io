---
layout: archive
image: 
    feature: logohorz.png
permalink: /
title: 
---
The Wet Lab is San Diego's premier hackerspace organization for biology and biotech, we're currently searching for new lab space.  The Wet Lab also collaborates with the La Jolla Riford Library **<a href="http://lajollalibrary.org/your-library/bio-lab/">Bio Lab</a>** and performs educational activities through the library. 

**<a href="{{ site.url }}/news">Wet Lab Updates:</a>**
<div class="tiles">
{% for post in site.categories.news %}
  {% include post-list.html %}
{% endfor %}
</div><!-- /.tiles -->
[//]: # ![bbl]({{ site.url }}/images/bbl.jpg)

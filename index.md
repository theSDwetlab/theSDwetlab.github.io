---
layout: archive
image: 
    feature: logohorz.png
permalink: /
title: 
---
The Wet Lab is San Diego's premier hackerspace for biotech, currently located within the **<a href="http://www.fablabsd.org/">Fab Lab</a>** at 847 14th St, San Diego, CA 92101.  The Wet Lab also collaborates with the La Jolla Riford Library **<a href="http://lajollalibrary.org/your-library/bio-lab/">Bio Lab</a>** and performs educational activities through the library. 
<div class="tiles">
{% for post in site.categories.news %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
[//]: # ![bbl]({{ site.url }}/images/bbl.jpg)

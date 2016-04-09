---
layout: archive
title: Projects
date: 2016-04-03T02:56:30-07:00
modified:
excerpt:
image:
  feature:
  teaser:
  thumb:
ads: false
---
<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

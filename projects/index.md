---
layout: home
permalink: projects
title: "Potential Research Projects"
excerpt: "For PhD, Masters or Honours"
image:
  feature: 20101020_099.jpg
---
<h2 class="post-title"> </h2>
<div class="tiles">
{% for post in site.categories.projects %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

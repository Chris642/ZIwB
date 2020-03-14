---
layout: project
title: Przedmioty
group: "navigation"
permalink: /przedmioty/
---

{% for project in site.projects %}

<div class="responsive">
  <div class="hvr-outline-in">
  <div class="gallery">
   <h2><a href="{{ project.url | prepend: site.baseurl}}"><img src="{{ project.image_path }}" style="width: 600; height: auto" alt="{{ project.title }}">{{ project.title }}</a></h2>
  <div class="desc">{{ project.desc }}</div>
  </div>
  </div>
</div>
{% endfor %}
<div class="clearfix"></div>

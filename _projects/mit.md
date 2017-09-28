---
layout: projectosite
title: TAGE
image_path: https://upload.wikimedia.org/wikipedia/commons/thumb/0/0c/MIT_logo.svg/2000px-MIT_logo.svg.png
desc: "Quick description."
---

TEXT TEST
{% for post in site.categories.mit_challenge %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url | prepend: site.baseurl}}">{{ post.title }}</a></li>
{% endfor %}

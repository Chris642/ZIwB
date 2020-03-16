---
layout: projectosite
title: Modele i narzędzia optymalizacji w systemach informatycznych zarządzania
image_path: https://upload.wikimedia.org/wikipedia/commons/thumb/d/d4/X-47B_operating_in_the_Atlantic_Test_Range_%28modified%29.jpg/640px-X-47B_operating_in_the_Atlantic_Test_Range_%28modified%29.jpg
desc: "W/L: dr hab. inż. Rafał Różycki"
---

TEXT TEST
{% for post in site.categories.mit_challenge %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url | prepend: site.baseurl}}">{{ post.title }}</a></li>
{% endfor %}

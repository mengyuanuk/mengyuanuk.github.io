---
layout: archive
title: "Photos"
permalink: /photos/
author_profile: true
---


Hello, here are some pictures about me and my daily life.


here is 
heihei

In the past five years, I have been to more than 20 countries and took a lot of pictures during my journeys. The [map](https://mengyuanuk.github.io/talkmap.html)
shows the city I have visited. If you are also interested in these places, maybe we can share tips on planning travel and saving money. 
<iframe src="/talkmap/map.html" height="700" width="850" style="border:none;"></iframe>

{% include base_path %}


{% for post in site.photos %}
  {% include archive-single.html %}
{% endfor %}


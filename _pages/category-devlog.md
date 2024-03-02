--- 
title: "개발일지"
layout: archive
permalink: /devlog
---

{% assign posts = site.categories.devlog %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}

--- 
title: "회의록"
layout: archive
permalink: /meeting
---

{% assign posts = site.categories.meeting %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}

--- 
title: "주간 다이어리"
layout: archive
permalink: /weekilyDiary
sidebar_main: true
author_profile: true
---

{% assign posts = site.categories.weekilyDiary %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}

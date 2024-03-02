--- 
title: "주간 다이어리"
layout: archive
permalink: /weeklyDiary
sidebar_main: true
author_profile: true
---

{% assign posts = site.categories.weeklyDiary %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}

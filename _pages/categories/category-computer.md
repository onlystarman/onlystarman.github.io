---
title: "computer"
layout: archive
permalink: categories/computer
author_profile: true
sidebar_main: true
---


{% assign posts = site.categories.COMPUTER %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}

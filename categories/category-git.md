---
title: "GIT"
layout: archive
permalink: categories/git
author_profile: true
sidebar_main: true
---


{% assign posts = site.categories.computer %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}
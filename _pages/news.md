---
layout: archive
permalink: /news/
title: "News"
author_profile: true
---

{% include base_path %}
{% for post in site.news %}
  {% include archive-single.html %}
{% endfor %}

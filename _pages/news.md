---
layout: archive
permalink: /news/
title: "News"
author_profile: true
---

{% include base_path %}
{% for post in site.news reversed %}
  {% include archive-single-news-page.html %}
{% endfor %}

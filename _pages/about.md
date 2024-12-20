---
permalink: /
title: "Welcome"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

As a researcher at the [Max Planck Institue for Informatics](https://www.mpi-inf.mpg.de/departments/inet), I focus on large scale analysis and measurements targeting the Internet. My core areas are the analysis of network deployments and their peculiarities. My work relies on multiple protocols spanning networking layers, such as IPv6, DNS, TLS, QUIC.
The goal is to reach a better understanding of the Internet and the impact of often disregarded influences such as Off-Net deployments.

Previously, I did my PhD at the [Chair of Network Architecures and Services](https://net.in.tum.de/) at the [Technical University of Munich](https://www.tum.de/en/).

I am co-leading the [Global Internet Observatory (GINO)](https://net.in.tum.de/projects/gino/), an interest focusing on Internet measurements. Over the years, we acquired vast knowledge in the area of large scale network measurements. This helps us to understand the current network state and its development. We seek to be harmless and conduct all measurements in an ethical manner.

Recent News
=====
[All news](/news)

<ul>
{% for post in site.news reversed limit:5%}
  {% include archive-single-news.html %}
{% endfor %}
</ul>

Selected Publications
======
[Full list of publications](/publications)

  <ul>{% for post in site.publications %}
    {% if post.important == "true" %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>


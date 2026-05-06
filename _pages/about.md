---
permalink: /
title: "Welcome"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

The Internet is constantly changing: new protocols are designed to improve services, e.g., performance, security, or service flexibility.
While Internet protocols are designed according to formal specifications, their real-world deployment often diverges in subtle but important ways.
This raises questions about how the Internet adapts to new protocols and the increasing complexity, and about whether design goals are met or can be further improved on.
My research at the [Max Planck Institue for Informatics](https://www.mpi-inf.mpg.de/departments/inet) focuses on understanding the Internet as a large-scale, evolving system through empirical measurement and data-driven analysis. I currently focus on the evaluation of the behavior of new protocols, e.g., QUIC, due to their increasing complexity, and their behavior within the network in addition to existing protocols.
My research is based on three pillars: (i) Internet measurements to identify and evaluate services, (ii) the development and evaluation of endpoint behavior to effectively make use of new protocols, and (iii) the evaluation and improvement of protocol behavior.
My work has informed both the research community and practitioners about the current state of the Internet ecosystem.
I regularly publish at leading networking venues such as ACM IMC, CoNEXT, and PAM.

Previously, I did my PhD at the [Chair of Network Architecures and Services](https://net.in.tum.de/) at the [Technical University of Munich](https://www.tum.de/en/).

I am co-leading the [Global Internet Observatory (GINO)](https://net.in.tum.de/projects/gino/), an interest focusing on Internet measurements. Over the years, we acquired vast knowledge in the area of large scale network measurements. This helps us to understand the current network state and its development.
We seek to be harmless and conduct all measurements in an ethical manner.

Recent News
=====
[All news](/news)

<ul>
{% assign items = site.news | reverse %}
{% for post in items limit:5%}
  {% include archive-single-news.html %}
{% endfor %}
</ul>

Selected Publications
======
[Full list of publications](/publications)

  <ul>{% for post in site.publications reversed %}
    {% if post.important == "true" %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>


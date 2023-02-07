---
title: "IPv6 Hitlist Service"
date: 2022-07-20
collection: news
---
  <style>
  
  img {
    max-width: 50%;
    max-height:15%;
    float: right;
  }
  
  </style>
<div class="container">
<div class="image">
<img src="/images/responsive-addresses-in.svg" alt="" border=3 height=100  width=500>
</div>
Alongside our <a href="/publication/2022-10-25-Rusty-Clusters-Dusting-an-IPv6-Research-Foundation">IMC 2022 publication</a> we updated the <a href="https://ipv6hitlist.github.io/">IPv6 Hitlist Service</a>.
We deployed the following updates:
<ul>
<li>We removed all responses to the UDP/53 scan injected by the Great Firewall of China (historically and for future scans)</li>
<li>We added new sources increasing the number of responsive addresses by roughly 5 Million to 7.2 Million.
Most addresses are from different target generation algorithms but also new passive sources.</li>
</ul>
We furthermore suggest that research relying on the IPv6 Hitlist evaluate whether addresses from fully responsive prefixes (aliased prefixes) should be included. For more information, we refer to our paper.
</div>

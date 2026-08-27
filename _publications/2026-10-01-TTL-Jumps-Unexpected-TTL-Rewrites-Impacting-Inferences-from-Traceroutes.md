---
title: "TTL Jumps: Unexpected TTL Rewrites Impacting Inferences from Traceroutes"
collection: publications
permalink: /publication/2026-10-01-TTL-Jumps-Unexpected-TTL-Rewrites-Impacting-Inferences-from-Traceroutes
important: "true"
date: 2026-10-01
venue: 'Proc. ACM Int. Measurement Conference (IMC)'
citation: 'Sebastian Kappes, Anja Feldmann, Tobias Fiebig, <b>Johannes Zirngibl</b>, &quot;TTL Jumps: Unexpected TTL Rewrites Impacting Inferences from Traceroutes.&quot; Proc. ACM Int. Measurement Conference (IMC), 2026.'
authors: 'Sebastian Kappes, Anja Feldmann, Tobias Fiebig, <b>Johannes Zirngibl</b>'
abstract: "Traceroute is an important Internet measurement tool used to infer the Internet’s topology and to identify middleboxes. It relies on network devices decrementing the Time to Live (TTL) in IP packet headers by one at each hop and sending Internet Control Message Protocol (ICMP) Time Exceeded error messages if the TTL reaches zero. However, we show that TTL jumps exist on the Internet: some devices rewrite the TTL, often to larger value of up to 255. These rewrites hide the remaining path from traceroute and can lead to incorrect inferences like spurious router and Autonomous System (AS) links. Based on controlled experiments and public data from RIPE Atlas and CAIDA Ark, we show that at least 47 ASes are impacted by path-impairing devices that rewrite the TTL. A prominent example is AT&T where more than 90 % of outgoing IPv6 paths from CAIDA Ark nodes are affected since 2023."
---
[<i class="ai ai-google-scholar"></i>](https://scholar.google.com/scholar?q=TTL+Jumps:+Unexpected+TTL+Rewrites+Impacting+Inferences+from+Traceroutes){: .btn--research-inverse} [Bib](/bibentries/kappes2026ttlrewrites.bib){: .btn--research-inverse} [<i class="fas fa-file-pdf"></i>](/files/kappes2026ttlrewrites.pdf){: .btn--research-inverse}
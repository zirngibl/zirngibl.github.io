---
title: "Punching Bag: A Tool for Testing IPv6 Scans and Target Generation Algorithms"
collection: publications
permalink: /publication/2026-10-01-Punching-Bag-A-Tool-for-Testing-IPv6-Scans-and-Target-Generation-Algorithms
important: "true"
date: 2026-10-01
venue: 'Proc. ACM Int. Measurement Conference (IMC)'
citation: 'Lion Steger, Christian Junginger, Georg Carle, <b>Johannes Zirngibl</b>, &quot;Punching Bag: A Tool for Testing IPv6 Scans and Target Generation Algorithms.&quot; Proc. ACM Int. Measurement Conference (IMC), 2026.'
authors: 'Lion Steger, Christian Junginger, Georg Carle, <b>Johannes Zirngibl</b>'
abstract: "Scanning the IPv6 address space exhaustively is infeasible. Besides hitlists with known active addresses, Target Generation Algorithms (TGAs) are a common tool for generating input for IPv6 measure- ments. They generate candidate addresses based on known respon- sive addresses using address patterns or machine learning. Some TGAs additionally use active scans during address generation as feedback mechanisms. However, the Internet is a changing ecosys- tem and scans can be impacted by network events, e.g., rate limits. These effects impact TGA results, a proper evaluation of their qual- ity and benefit, and the comparability of TGAs. We propose an IPv6 Punching Bag, a local environment to test IPv6 scans and TGAs before actually using them on the Internet. It allows configuring prefixes with different response rates, e.g., aliased prefixes, or address patterns. It can be used on a single machine with a low memory footprint. We evaluate six dynamic TGAs with the Punching Bag and show that their adherence to scanning budgets and limits, and their inabil- ity to detect aliased prefixes necessitates local tests before Internet scans. We also demonstrate that 6Scan, a dynamic TGA, is not adapting to different response behavior."
---
[<i class="ai ai-google-scholar"></i>](https://scholar.google.com/scholar?q=Punching+Bag:+A+Tool+for+Testing+IPv6+Scans+and+Target+Generation+Algorithms){: .btn--research-inverse} [Bib](/bibentries/steger2026punching.bib){: .btn--research-inverse} [<i class="fas fa-file-pdf"></i>](/files/steger2026punching.pdf){: .btn--research-inverse} [Homepage](https://github.com/tumi8/punching-bag){: .btn--research}

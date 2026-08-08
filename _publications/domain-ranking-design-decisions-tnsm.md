---
title: "Evaluating Design Decisions and Bias Resistance for Passive DNS-Based Domain Rankings"
authors: "Le Pochat, Victor; Fernandez, Simon; Tajalizadehkhoob, Samaneh; Desmet, Lieven; Duda, Andrzej; Joosen, Wouter; Korczyński, Maciej"
collection: publications
permalink: /publication/domain-ranking-design-decisions-tnsm
excerpt: "We evaluate how recent design decisions in 'top sites' rankings influence the composition and desired properties of passive DNS-based domain rankings, including resistance to inadvertent or malicious biases."
abstract: "'‘Top sites’ rankings of the most popular domains are a core resource for the large-scale measurements that are crucial in Web and Internet research. Recent rankings evolved towards using passive DNS traffic data, but this data’s suitability for measuring website popularity is poorly understood. In this paper, we holistically evaluate how design decisions influence the composition and desired properties of passive DNS-based domain rankings. We isolate the effects of these decisions by generating a ranking from the ground up using aggregated “post-recursor” passive DNS data. We confirm that decisions for bucketing and aggregation produce more stable rankings, and see that corrections for resolver caching, CDNs, and service classification strongly impact suitability for Web measurements. We further analyze the resistance of rankings to inadvertent biases or even active manipulation, and find that design choices such as TTL weighting severely impact robustness. Our goal is to give transparent insight into the process of using passive DNS data for domain rankings, as a framework for the research community to understand how to develop future rankings that address their needs."
date: 2026-06-18
venue: 'IEEE Transactions on Network and Service Management'
venue_short: 'TNSM'
paperurl: '/files/domain-ranking-design-decisions-tnsm26.pdf'
doi: '10.1109/TNSM.2026.3705306'
bibtex: |
    @article{LePochat2026designdecisions,
     author = {Le Pochat, Victor and Fernandez, Simon and Tajalizadehkhoob, Samaneh and Desmet, Lieven and Duda, Andrzej and Joosen, Wouter and Korczyński, Maciej},
     title={Evaluating Design Decisions and Bias Resistance for Passive DNS-Based Domain Rankings}, 
     journal={IEEE Transactions on Network and Service Management}, 
     year={2026},
     volume={23},
     pages={5467-5480},
     doi={10.1109/TNSM.2026.3705306}
    }
---

---
title: "How Did You Find That Address? An In-Depth Investigation of Domain-Based IPv6 Scanners"
authors: "Kappes, Sebastian; Steger, Lion; Le Pochat, Victor; Gasser, Oliver; Zirngibl, Johannes; Heinrich, Tiago"
collection: publications
permalink: /publication/domain-based-ipv6-scanners
excerpt: "We investigate how IPv6 scanners rely on domain names for target reconnaissance."
abstract: "IPv6’s vast address space makes scanning particularly challenging. IPv6 scanners must first discover in-use IPv6 addresses they can target and scan. One way of doing this is by collecting IPv6 addresses from domain names: if a DNS name resolves to an IPv6 address, that address is more likely to be used by an actual live host.
  In this study, we investigate how IPv6 scanners rely on domain names for target reconnaissance. We set up a large IPv6 telescope to which we attract scanners by placing honey domain names on TLD zone files, CT logs, and the Tranco Top 1M. We introduce a technique to trace the packets that IPv6 scanners send to the telescope back to the initial DNS queries they sent to discover the IPv6 addresses, allowing us to better evaluate how large-scale IPv6 scanners collect and scan addresses. Over a period of six months, we collect 9.4 M IPv6 scan packets from 25 k addresses in 613 ASes. We find that domain-based IPv6 scanners differ in their address collection strategies, which also correlates with different scanner behavior: scanners that scan addresses hours after collecting them send mostly ICMP traffic, while scanners that resolve domains and scan addresses in one go are more focused on TCP/UDP—many of the latter are also not limited to IPv6 and will fall back to IPv4 if necessary. We uncover that scanners often combine (in particular, open) domain sources to find more targets, and that different domain sources attract different scanners. We also demonstrate that the IPv6 Hitlist is a strong mediating factor when attracting scanners through domain names, which we address by excluding our telescope’s address space from the Hitlist. Furthermore, we use our fine-grained packet tracing to detect distributed scanning campaigns involving multiple ASes and to distinguish different scanners within large cloud ASes. Our findings show a diverse landscape of domain-based IPv6 scanning on the Internet: different scanners employ distinct scanning strategies and rely on unique domain sources, which greatly impacts how researchers should study them."
date: 2026-12-07
venue: '22nd International Conference on emerging Networking EXperiments and Technologies'
venue_short: 'CoNEXT'
paperurl: '/files/domain-based-ipv6-scanners-conext26.pdf'
doi: '10.1145/3830390'
bibtex: |
    @article{kappes2026how,
     author = {Kappes, Sebastian and Steger, Lion and Le Pochat, Victor and Gasser, Oliver and Zirngibl, Johannes and Heinrich, Tiago},
     title = {{How Did You Find That Address? An In-Depth Investigation of Domain-Based IPv6 Scanners}},
     year = {2026},
     volume = {4},
     issue_date = {September 2026},
     number = {CoNEXT3},
     doi = {10.1145/3830390},
     journal = {Proceedings of the ACM on Networking},
     month = sep,
     articleno = {35},
     numpages = {25},
    }

---

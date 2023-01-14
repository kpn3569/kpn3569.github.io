---
title: "CuVPP: Filter-based Longest Prefix Matching in Software Data Planes"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-3
excerpt: 'Programmability in the data plane has become increasingly important as virtualization is introduced into networking and software-defined networking becomes more prevalent. Yet, the performance of programmable data planes on commodity hardware is a major concern, in light of ever-increasing network speed and routing table size. This paper focuses on IP lookup, specifically the longest prefix matching for IPv6 addresses, which is a major performance bottleneck in programmable switches. As a solution, the paper presents CuVPP, a programmable switch that uses packet batch processing and cache locality for both instructions and data by leveraging Vector Packet Processing (VPP). We thoroughly evaluate CuVPP with both real network traffic and file-based lookup on a commodity hardware server connected via 80 Gbps network links and compare its performance with the other popular approaches. Our evaluation shows that CuVPP can achieve up to 4.5 million lookups per second with real traffic, higher than the other trie- or filter-based lookup approaches, and scales well even when the routing table size grows to 2 million prefixes.'
date: 2015-10-01
venue: 'IEEE International Conference on Cluster Computing (CLUSTER)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9229596'
citation: ' Kwon, Minseok, Neupane, Krishna, et.al. International Conference on Cluster Computing (CLUSTER) 2020'
---

[Download paper here]([(https://ieeexplore.ieee.org/abstract/document/9229596)])

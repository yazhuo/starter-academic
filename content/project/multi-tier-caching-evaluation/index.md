---
title: Multi-Tier Caching Evaluation
date: 2021-05-17T21:39:06.661Z
summary: ""
draft: false
featured: false
external_link: ""
links: []
image:
  filename: ""
  focal_point: Smart
  preview_only: false
---

While distributed caches are central to today’s ever-growing content-distribution networks, they are difficult to configure and operate. Minor changes to the cache topology, resource upgrades, or modification of replacement policy can have significantly affect user-perceived latency and the back-end storage system loads, even under relatively stable workloads. 

Rather than having cache system operators navigate potential impact from such changes through trial and error, we propose counterfactual cache modeling (CCM) to analyze distributed cache performance even under hypothetical changes to the cache topology, layering or resource configuration, such as cache size. Harnessing prior work for producing cache miss-ratio curves (MRC) in single caches, we define CCM to comprise mathematical addition, scaling, sampling, and filtering operators over input workloads in multi-tier cache settings, and discuss how these operators can be implemented efficiently. 

The work is still ongoing.

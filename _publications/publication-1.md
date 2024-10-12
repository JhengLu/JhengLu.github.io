---
title: "Mercury: QoS-Aware Tiered Memory System"
excerpt: "<b>Jiaheng Lu*</b>, Yiwen Zhang, Hasan Maruf, Minseo Park, Yunxuan Tang, Rita Gupta, Fan Lai, Mosharaf Chowdhury. 
<br>In submission to <em>OSDI</em>, 2024
<br>* Equal contribution
<br><a href="#">Paper</a>, <a href="#">Code</a>"
collection: publications
---

[//]: # (<b>Jiaheng Lu*</b>, Yiwen Zhang, Hasan Maruf, Minseo Park, Yunxuan Tang, Rita Gupta, Fan Lai, Mosharaf Chowdhury.)

[//]: # (<br>In submission to <em>OSDI</em>, 2024)

[//]: # (<br>* Equal contribution)

[//]: # (<br>[[Paper]&#40;#&#41;], [[Code]&#40;#&#41;])
<h2>Abstract</h2>
Tiered memory systems have widely been adopted to provide larger memory capacity in response to increasing memory demands from memory-intensive workloads.
Although increased memory capacity allows more applications to be deployed, existing solutions for tiered memory systems are not built with Quality-of-Service (QoS) support.
As a result, they often cannot meet service-level objectives (SLOs) when multiple applications share a tiered memory system.
Specifically, applications suffer from **local memory contention** and **memory bandwidth interference**, two sources of performance unpredictability unique to tiered memory systems.
Indeed, we observe application performance drops by 43\% and 70\% during severe memory contention and interference.

This paper presents Mercury, a QoS-aware tiered memory system that provides predictable performance for coexisting memory-intensive applications, each with different SLOs.
Mercury enables per-tier page reclamation to enforce application-level resource management.
It leverages a novel admission control and real-time adaptation algorithm to maximize local memory utilization while mitigating memory interference.
Evaluations with real-world applications show that Mercury can provide QoS guarantees among multiple applications sharing a tiered memory system with up to 53.4\% improvement in performance.

<br>
**Materials**
<ul>
<li><a href="#">Paper</a></li>
<li><a href="https://github.com/SymbioticLab/Mercury">Code</a></li>
</ul>


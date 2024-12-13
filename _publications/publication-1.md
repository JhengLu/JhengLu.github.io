---
title: "Mercury: QoS-Aware Tiered Memory System"
excerpt: "<strong>Jiaheng Lu*</strong>, Yiwen Zhang*, Hasan Al Maruf, Minseo Park, Yunxuan Tang, Fan Lai, Mosharaf Chowdhury.
<br>In submission to <em><strong>OSDI</strong></em>, 2025
<br>* Equal contribution
<br>[<a href='https://arxiv.org/abs/2412.08938'>Paper</a>], [<a href='https://github.com/SymbioticLab/Mercury'>Code</a>]"
collection: publications
---

[//]: # (<b>Jiaheng Lu*</b>, Yiwen Zhang, Hasan Maruf, Minseo Park, Yunxuan Tang, Rita Gupta, Fan Lai, Mosharaf Chowdhury.)

[//]: # (<br>In submission to <em>OSDI</em>, 2025)

[//]: # (<br>* Equal contribution)

[//]: # (<br>[[Paper]&#40;#&#41;], [[Code]&#40;#&#41;])
<h2>Abstract</h2>
Memory tiering has received wide adoption in recent years as an effective solution to address the increasing memory demands of memory-intensive workloads. However, existing tiered memory systems often fail to meet service-level objectives (SLOs) when multiple applications share the system because they lack Quality-of-Service (QoS) support. Consequently, applications suffer severe performance drops due to local memory contention and memory bandwidth interference.
In this paper, we present Mercury, a QoS-aware tiered memory system that ensures predictable performance for coexisting memory-intensive applications with different SLOs. Mercury enables per-tier page reclamation for application-level resource management and uses a proactive admission control algorithm to satisfy SLOs via per-tier memory capacity allocation and intra- and inter-tier bandwidth interference mitigation. It reacts to dynamic requirement changes via real-time adaptation. Extensive evaluations show that Mercury improves application performance by up to 53.4% and 20.3% compared to TPP and Colloid, respectively.
<br>
<img src='/images/mercury_overview_new.pdf'>
<p><center><b>Architecture</b></center></p>

**Materials**
<ul>
<li><a href="https://arxiv.org/abs/2412.08938">Paper</a></li>
<li><a href="https://github.com/SymbioticLab/Mercury">Code</a></li>
</ul>


---
title: "Rusen: Rule Semantics Enabler toward Fast TCAM Update for Commodity SDN Switches"
collection: publications
permalink: /publication/Rusen
excerpt: ' Hao Mei, Ruoshi Sun, **Ruyi Yao**, Chuhao Chen, Cong Luo, Zixuan Chen, Jiahui Li, Sen Liu, Yang Xu'
date: 2023-06-19
venue: 'IWQoS'
---

Ternary Content Addressable Memory (TCAM) is widely used in Software-Defined Networking (SDN) switches due to its impressive throughput. But its unique circuit design results in long and inconsistent update delays. To overcome this challenge, many TCAM update algorithms based on rule semantics have been proposed. These algorithms eliminate unnecessary order restrictions, thus reducing update delays in theory. However, most commodity switches are semantic-unaware, which maintain rules in strict priority order. These algorithms are therefore not available for practical use. To address this issue, this paper proposes Rusen, a framework that enables the use of many semantic-based algorithms on Semantic-unaware commodity switches. Working as a transparent middle layer, the core idea of Rusen is to express the update scheme derived by semantic-based algorithms as messages that the Semantic-unaware switches can execute. In addition, Rusen optimizes the update scheme based on the specific characteristics of each switch, leading to improved performance of these algorithms. We evaluate the performance of Rusen by enabling several state-of-the-art semantic-based algorithms on commodity SDN switches. Results show that the average update delay can be significantly reduced by 23%∼94% on OpenFlow switches and 39%∼84% on a P4 switch.

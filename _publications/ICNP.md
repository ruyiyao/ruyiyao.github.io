---
title: "MagicTCAM: A Multiple-TCAM Scheme for Fast TCAM Update"
collection: publications
permalink: /publication/ICNP
excerpt: 'Ruyi Yao, Cong Luo, Xuandong Liu, Ying Wan, Bin Liu, Wenjun Li, Yang Xu'
date: 2021-11-03
venue: 'ICNP'
---
Ternary Content-Addressable Memory (TCAM) is a popular solution for high-speed flow table lookup in Software-Defined Networking (SDN). 
Rule insertion in TCAM is a time-consuming operation. To ensure semantic correctness, rules overlapped must be stored in TCAM with decreasing priority order and many rule movements may be needed to make space for a single inserted rule.  When a rule insertion is in progress, the regular flow table lookup will be suspended, which could lead to a degraded user experience for SDN applications. In this paper, we propose a multiple-TCAM framework named MagicTCAM to reduce the rule movements during a rule insertion. The core of MagicTCAM lies in three operations: \textit{layering}, \textit{partitioning} and \textit{rotating}. By layering, rules with the least overlapping will be grouped (i.e., layered) into a sub-ruleset. The number of rule movements is therefore greatly reduced as most of rules in a sub-ruleset are non-overlapped. To achieve balanced load in TCAMs, rules in each sub-ruleset are further partitioned and dispatched into different TCAMs in a rotating manner. In addition, an inter-TCAM movement algorithm is proposed to allow rules to be moved between TCAMs for reduced rule movement. Experiment results show that with two half-sized TCAMs, MagicTCAM reduces the rule movements by 39\% on average compared with the state-of-the-art work while the computation time is shortened by half as well.

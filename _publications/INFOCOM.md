---
title: "CoLUE: Collaborative TCAM Update in SDN Switches"
collection: publications
permalink: /publication/INFOCOM
excerpt: 'Ruyi Yao, Cong Luo, Hao Mei, Chuhao Chen, Wenjun Li, Ying Wan, Sen Liu, Bin Liu, Yang Xu.'
date: 2023-05-16
venue: 'INFOCOM'
---

With the rapidly changing network, rule update in TCAM has become the bottleneck for application performance. In traditional software-defined networks, some application policies are deployed at the edge switches, while the scarce TCAM spaces exacerbate the frequency and difficulty of rule updates. This paper proposes CoLUE, a framework which groups rules into switches in a balance and dependency minimum way. CoLUE is the first work that combines TCAM update and rule placement, making full use of TCAM in distributed switches.  Not only does it accelerate update speed, it also keeps the TCAM space load-balance across switches. 
Composed of ruleset decomposition and subset distribution, CoLUE has an NP-completeness challenge. We propose heuristic algorithms to calculate a near-optimal rule placement scheme. Our evaluations show that CoLUE effectively balances TCAM space load and reduces the average update cost by more than 1.45 times and the worst-case update cost by up to 5.46 times, respectively.




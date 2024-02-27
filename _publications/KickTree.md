---
title: "KickTree: A Recursive Algorithmic Scheme for Packet Classification with Bounded Worst-Case Performance"
collection: publications
permalink: /publication/KickTree
excerpt: 'Yao Xin, Yuxi Liu, Wenjun Li, **Ruyi Yao**, Yang Xu, Yi Wang'
date: 2021-09-11
venue: 'ANCS'
---

As a promising alternative to TCAM-based solutions for packet classification, FPGA has received increasing attention. Although extensive research has been conducted in this area, existing FPGA-based packet classifiers cannot satisfy the burgeoning needs from OpenFlow, which demands large-scale rule sets and frequent rule updates. As a recently proposed hardware-specific approach, TabTree avoids rule replication and supports dynamic rule update. However, it still faces problems of unbalanced rule subset partition, unevenly distributed subtrees and excessive TSS leaf nodes when implemented on FPGA. In this paper, we propose a hardware-friendly packet classification approach called KickTree, which is elaborated by considering hardware properties. To take advantage of intrinsic parallelism of FPGA, KickTree adopts multiple balanced decision trees which can run simultaneously. The bit selection is more flexible which breaks the restriction of rule subset. Moreover, each subset size is strictly limited, leading to bounded and evenly-distributed trees. Experimental results show KickTree outperforms TabTree significantly in terms of the number of memory accesses
for each classification operation while providing a rule update performance comparable to TabTree. In summation,
KickTree is more practical for implementations on FPGA.

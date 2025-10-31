---
title: "CClinguist: An Expert-Free Framework for Future-Compatible Congestion Control Algorithm Identification"
collection: publications
permalink: /publication/CClinguist
excerpt: 
date: 2025-08-27
venue: 'SIGCOMM'
fields: "Network Performance Optimization -  Congestion Control"
---

Jiahui Li, Han Qi, **Ruyi Yao**, Jialin Wei, Ruoshi Sun, Zixuan Chen, Sen Liu, and Yang Xu.


**Fields**: Network Performance Optimization -  Congestion Control. 

**Abstract**: Congestion control algorithms (CCAs) play a critical role in determining transmission quality. With their rapid evolution during the past few decades, understanding the CCA landscape on the Internet has become increasingly essential for network advancement. Traditional CCA census tools, however, rely heavily on manual configuration and construction, necessitating significant human effort to keep pace with the introduction of new CCAs.
In this paper, we introduce the CClinguist framework, which is an expert-free CCA identification tool. It mainly comprises a network profile auto-generator and a self-learning classifier to accommodate emerging CCAs and new network scenarios, ensuring future compatibility in both the temporal and spatial aspects of the network census. We also develop a prototype of CClinguist and evaluate its performance. The results demonstrate that CClingusit can accurately identify 12 known CCAs in the Linux kernel with 97.33% accuracy. Notably, it maintains high accuracy with new scenarios and emerging CCAs, including learning-based and ECN-based CCAs, outperforming state-of-the-art identification tools. When applied to a census of over 7,000 web servers, CClinguist successfully detects unknown CCA variants and is able to explore the support of ECN on web servers.

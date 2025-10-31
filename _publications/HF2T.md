---
title: "Empowering Flowlet Load Balancing in RDMA with Host-Based Flowlet Fine-Tuning"
collection: publications
permalink: /publication/HF2T
excerpt: 
date: 2025-07-02
venue: 'IWQoS'
fields: "Network Performance Optimization -  Load Balance"
---

Chuhao Chen, Deli Huang, Zerui Tian, **Ruyi Yao**, Jing Jiang, Sen Liu & Yang Xu.

**Fields**: Network Performance Optimization -  Load Balance.

**Abstact**: Flowlet-level load balancing has not demonstrated the expected robust capability in RDMA networks due to insufficient flowlets and the adverse effects of PFC. To delve deeper, we conduct measurements at end hosts and perform a detailed analysis of time gaps between packets. Our investigation reveals that in RDMA networks, the number of time gaps exceeding the flowlet timeout is considerably lower than the number in TCP networks. We also identify a stepwise time gap pattern that predicts the occurrence of PFC. Based on these observations, we propose HF2T, a host-based time gap adjustment method to improve the effectiveness of flowlet-level load balancing in RDMA networks. The core idea involves delaying a minimal number of specific packets at the host, actively extending the time gaps between them, thereby fostering the generation of sufficient flowlets at the switch and enhancing the utilization of equal-cost links. Incorporating an identification algorithm for the time gap pattern that predicts PFC, HF2T also leverages the time gap extension to reroute traffic away from potential PFC paths in advance, thus mitigating PFC occurrences. The minor cost of delaying a few packets is vastly offset by the benefits of generating flowlets and reducing PFC. We use DPDK to implement a prototype of HF2T, and through testbed experiments, we demonstrate that HF2T, serving as a building block for flowlet load balancing, can enhance the throughput of CONGA by 16.82%. The simulation results also show that HF2T can reduce the average FCT by 16.38% and the 99-percentile FCT by 21.13% compared to the state-of-the-art RDMA load balancing ConWeave.

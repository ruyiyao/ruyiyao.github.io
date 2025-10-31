---
title: "PIPO: Efficient Programmable Scheduling for Time Sensitive Networking"
collection: publications
permalink: /publication/PIPO
excerpt: 'Chuwen Zhang, Zhikang Chen, Haoyu Song, **Ruyi Yao**, Yang Xu, Yi Wang, Ji Miao, Bin Liu'
date: 2021-11-03
venue: 'ICNP'
fields: "Programmable Data Plane - Programmable Packet Scheduling for Time Sensitive Networking"
---

**Fields**: Programmable Data Plane - Programmable Packet Scheduling for Time Sensitive Networking. 

Time Sensitive Networking (TSN) is an emerging Ethernet technology for real-time systems. To address different Quality-of-Service (QoS) requirements of applications, IEEE 802.1 TSN Task Group has standardized several packet scheduling and shaping algorithms. The software implementation of these algorithms is hard to meet the performance requirements, while the hardware implementation in Application-Specific Integrated Circuit (ASIC) is inflexible. A hardware-programmable scheduler is necessary to deal with this dilemma. Among the existing primitives, the most expressive one is Push-In-Extract-Out (PIEO), but its complexity makes the implementation very expensive. A relatively lower-cost implementation of PIEO cannot guarantee the scheduling correctness for the most critical Time-Triggered (TT) traffic in TSN. As a remedy, in this paper we propose a new Push-In-Pick-Out (PIPO) primitive under a TSN programmable scheduling framework. Composed of simple priority queues, PIPO can express all existing TSN scheduling and shaping algorithms, and is flexible enough to support future ones. Our PIPO implementation guarantees the TT traffic scheduling correctness. The simulation results corroborate the theoretical analysis that the low-cost PIPO can closely approximate PIEO and sustain a high bandwidth utilization. The prototype on Xilinx FPGA shows that, with 2,048 inputs, the PIPO-based scheduler achieves a throughput of 70 Mpps, which is 1.64x higher than the PIEO-based one, but using only 14.7\% Look-Up Tables (LUTs) and 40.5\% Block RAMs of the latter.

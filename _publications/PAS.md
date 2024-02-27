---
title: "Packet-size aware scheduling algorithms in guard band for time sensitive networking"
collection: publications
permalink: /publication/PAS
excerpt: 'Chuwen Zhang, Yi Wang, **Ruyi Yao**, Boyang Zhou, Liang Cheng, Yang Xu, Xiaoguang Li, Jian Cheng, Bin Liu.'
date: 2020-09-11
venue: 'CCF Transactions on Networking'
---

As an emerging and promising technology, Time Sensitive Networking (TSN) can be widely used in many real-time systems such as Industrial Internet of Things (IIoT) and Cyber Physical System (CPS). TSN, while ensuring the bounded latency and jitter, exhibits the disadvantage of not being able to efficiently use the bandwidth resources in the guard band. In this paper, we propose an algorithm family named Packet-size Aware Shaping (PAS), which is inspired by abstracting the problem of utilizing the guard band to a classic Precedence-Constrained Knapsack Problem (PCKP). PAS works with the existing TSN standards, having achieved the goal of guaranteeing the end-to-end latency for scheduled time-sensitive applications while fully utilizing the available bandwidth in the guard band for others. Furthermore, we have proposed and implemented several hardware designs for both the current standard TSN scheduler and the programmable one. The simulation results show that the PAS family can achieve satisfying performance in maximizing the resource utilization in the guard band. The synthesis results on Xilinx Vivado show that our proposed Multi-group Push-In-First-Out (MPIFO) scheduler can achieve 100 Mpps scheduling rate for 1024 scheduling items, which is fast enough to support the high-speed TSN.

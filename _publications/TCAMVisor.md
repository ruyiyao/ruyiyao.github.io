---
title: "TCAMVisor: High-throughput TCAM Virtualization for Multi-tenant Software Defined Networking"
collection: publications
permalink: /publication/TCAMVisor
excerpt: 'Ruoshi Sun, Hao Mei, **Ruyi Yao**, Hao Wang, Yiren Zhou, Zixuan Chen, Sen Liu, and Yang Xu'
date: 2024-06-19
venue: 'IWQoS'
honors: "Best Paper Honorable Mention"
fields: "Software Defined Networking - Flow Table Update"
---

**Honors**: Best Paper Honorable Mention, IEEE/ACM IWQoS，2024
**Fields**: Software Defined Networking - Flow Table Update. 

Software Defined Networking (SDN) provides users with a unified abstraction of physical networks. 
To meet the demands of modern data centers, many works have focused on designing network virtualization hypervisors that support multi-tenant SDN. 
Ternary Content Addressable Memory (TCAM) is widely used in SDN switches for rule storage. 
While it has extremely high lookup throughput, it also features drawbacks such as small capacity and slow update speed. Faced with multi-tenant scenarios, its limitations are even more pronounced. Existing hypervisors lack consideration for TCAM isolation, leading to slower TCAM updates and the mutual impact of requests from different tenants. Consequently, they fail to provide guaranteed performance to tenants. To solve these problems, we propose TCAMVisor, which further isolates TCAM resources based on traditional SDN hypervisors. Specifically, TCAMVisor provides better allocation mechanisms for TCAM entry and control bandwidth, ensuring inter-tenant isolation while improving resource utilization. Additionally, TCAMVisor improves the update speed of TCAM by delicately placing tenant rules.
To the best of our knowledge, TCAMVisor is the first work to effectively achieve tenant isolation in TCAM, with an average throughput improvement of 5.5 times compared to FlowVisor. 

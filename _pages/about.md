---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome :wave: I am a fifth-year Ph.D. student at the [Department of Electrical Engineering](https://www.ee.cityu.edu.hk/), City University of Hong Kong, Hong Kong SAR, under the supervision of [Prof. Lin DAI](https://www.ee.cityu.edu.hk/~lindai/). Prior to this, I received the B.Eng. degree in the School of Electronic Information and Communications from the [Huazhong University of Science and Technology](https://english.hust.edu.cn/), Wuhan, China, in 2020. My current research focuses on the decentralized multiple access, learning-based access design and next-generation wireless communication networks.
<br/>
<br/>
<h1 id="research">Research Interests</h1>
---
* **Decentralized multiple access**: Modeling, analysis and optimal design.
* **Next-generation wireless communication networks**: Massive Internet of Things, low-latency communications, and distributed learning-based access design.
<br/>
<br/>
<h1>Research Projects</h1>
---
<font size=5><b>:book: Queueing-Theoretical Analysis for Learning-Based Access Design</b></font>
---
Random access networks have long been observed to suffer from low throughput if nodes' access strategy is not properly designed. To improve the throughput performance, learning-based approaches, with which each node learns from the observations and experience to determine its own access strategy, have shown immense potential, but are often designed empirically due to the lack of theoretical guidance.

As we demonstrated in our recent work, the **queueing-theoretical analysis** can be leveraged as a powerful tool for **optimal design of learning-based access**. Specifically, based on a Multi-Armed-Bandit (MAB) framework, two random access schemes, MTOA-L with local rewards and MTOA-G with global rewards, are proposed for throughput optimization. Though both can achieve the maximum throughput of 1, they have different short-term fairness performance. Through identifying the access strategies learned via MTOA-L and MTOA-G and feeding them into the proposed unified queueing-theoretical framework, the **throughput-fairness tradeoff** of each is characterized and optimized by properly tuning the key parameters. The comparison of the optimal tradeoffs shows that MTOA-G is much superior to MTOA-L especially when the number of nodes is large.

:paperclip: **Related Paper**
* X. Zhao and L. Dai, "Throughput-Optimal Random Access: A Queueing-Theoretical Analysis for Learning-Based Access Design," submitted for publication. [[Preprint](https://)]

<font size=5><b>:book: A Unified Analytical Framework for Random Access</b></font>
---
As one of the two fundamental types of multiple access, random access has been widely applied in communication networks including cellular networks and WiFi networks. With random access, each node **independently** decides when to transmit. The distributed nature makes it especially appealing for next-generation wireless communication networks where Machine-to-Machine (M2M) communications is expected to play a dominant role.

Despite extensive applications and continuous attention for almost half a century, many fundamental issues pf random access remain unresolved. The challenge originates from the lack of unified analytical frameworks. Existing analytical models are often tailored for specific performance metrics or access protocols, where differences in modeling assumptions and definitions have led to inconsistent findings.

Essentially, a random access network can be regarded as a multi-queue-single-server system. The key to analyze its performance lies in properly modeling services processes of nodes' queues. By properly modeling the behavior of Head-of-Line (HOL) packets in each node's queue and establishing the fixed-point equations of steady-state probability of successful transmission of HOL packets, the service processes of nodes' queues can be characterized, based on which the network performance (e.g., throughput, delay and fairness) can further be analyzed and optimized.

<!-- The analysis not only reveals fundamental performance limits of random access networks, but also sheds important light on the access design of next-generation communication networks. -->

:paperclip: **Related Papers**:
* X. Zhao and L. Dai, "[To Sense or Not To Sense: A Delay Perspective](https://ieeexplore.ieee.org/document/10750858)," to appear in *IEEE Transactions on Communications*.

* X. Zhao and L. Dai, "[Connection-Based Aloha: Modeling, Optimization, and Effects of Connection Establishment](https://ieeexplore.ieee.org/document/10154598)," in *IEEE Transactions on Wireless Communications*, vol. 23, no. 2, pp. 1008-1023, Feb. 2024.

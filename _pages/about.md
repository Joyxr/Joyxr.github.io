---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome :wave: I am a researcher at the [Department of Electrical Engineering](https://www.ee.cityu.edu.hk/), City University of Hong Kong, Hong Kong SAR, under the supervision of [Prof. Lin DAI](https://www.ee.cityu.edu.hk/~lindai/). Prior to this, I received the Ph.D. degree in the Department of Electrical Engineering, City University of Hong Kong, in 2025, and the B.Eng. degree in the School of Electronic Information and Communications from the [Huazhong University of Science and Technology](https://english.hust.edu.cn/), Wuhan, China, in 2020. My current research focuses on the distributed multiple access, learning-based access design and next-generation wireless communication networks.
<br/>
<br/>
<h1 id="research">Research Interests</h1>
---
* **Distributed multiple access**: Modeling, analysis and optimal design.
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
* X. Zhao and L. Dai, "Throughput-Optimal Random Access: A Queueing-Theoretical Analysis for Learning-Based Access Design," submitted for publication. [[Preprint available](https://arxiv.org/abs/2504.03178)]

<font size=5><b>:book: Modeling and Optimization of Random Access Networks for M2M Communications</b></font>
---
With the rapid development of Machine-to-Machine (M2M) communications, random access, with which nodes independently decide when to transmit, has been regarded as an appealing solution due to its distributed nature. Due to the lack of unified analysis for different types of random access, nevertheless, many fundamental issues remain unresolved, e.g., optimal tuning of access parameters and effects of various access design features. To tackle these issues, in our recent works,

- **A unified analytical framework** was established, where **various design features** of random access, including sensing-free or sensing-based, connection-free or connection-based and backoff, were incorporated.
- Based on the unified framework, the **throughput and delay performance** of various random access schemes was characterized in a unified manner, and further optimized by properly tuning the access parameters such as transmission probability of each node.
- **Useful criteria**, such as the upper bound of sensing time for beneficial sensing, were obtained.
- The analysis was further applied to **practical random access schemes**, which sheds important light on the access design of next-generation communication networks.

<!-- In enabling the massive access of MTDs for M2M communications, random access has played a pivotal role. With random access, nodes independently decide when to transmit, which avoids heavy scheduling overhead thanks to its distributed and low-cost nature. Due to the lack of coordination among nodes, nevertheless, concurrent transmissions may collide, leading to transmission failures and causing excessively long delay in retransmissions if the access parameters are not properly selected.

To reduce the collisions, various random access schemes have been proposed and applied in practical communication systems. For instance, one way is to use Carrier Sense Multiple Access (CSMA), with which nodes first sense the channel, and transmit only if the channel is idle. Alternatively, connection-based random access can be adopted to alleviate the collisions, with which each node reserves the channel for data transmission by establishing a connection. Besides, properly designed backoff schemes can also effectively resolve the collisions. -->

<!-- Despite plenty of variants and extensive applications, many fundamental issues of random access remain unresolved, e.g., under what conditions carrier sensing or connection establishment is beneficial to the delay performance, which is of great interest considering the growing demand for supporting low-latency services in M2M communications. The challenge originates from the lack of unified analysis of random access schemes with different design features. -->

:paperclip: **Related Papers**:
* X. Zhao and L. Dai, "[To Sense or Not To Sense: A Delay Perspective](https://ieeexplore.ieee.org/document/10750858)," in *IEEE Transactions on Communications*, vol. 73, no. 6, pp. 3863-3879, June 2025.

* X. Zhao and L. Dai, "[Connection-Based Aloha: Modeling, Optimization, and Effects of Connection Establishment](https://ieeexplore.ieee.org/document/10154598)," in *IEEE Transactions on Wireless Communications*, vol. 23, no. 2, pp. 1008-1023, Feb. 2024.

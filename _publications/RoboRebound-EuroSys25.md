---
title: "RoboRebound: Multi-Robot System Defense with Bounded-Time Interaction"
collection: publications
permalink: /publication/RoboRebound-EuroSys25/
excerpt: ''
date: 2025-03-30
venue: 'European Conference on Computer Systems (EuroSys), 2025'
status: 'In'
paperurl: 'https://www.yifancai.tech/files/RoboRebound-Eurosys25.pdf'
authors: 'Neeraj Gandhi, <b>Yifan Cai</b>, Andreas Haeberlen, and Linh Thi Xuan Phan'
---

### Authors 

Neeraj Gandhi, **Yifan Cai**, Andreas Haeberlen, and Linh Thi Xuan Phan

### Abstract 

Byzantine Fault Tolerance (BFT) is a classic technique for defending distributed systems against a wide range of faults and attacks. However, existing solutions are designed for systems where nodes can interact only by exchanging messages. They are not directly applicable to systems where nodes have sensors and actuators and can also interact in the physical world– perhaps by blocking each other’s path or by crashing into each other.

In this paper, we take a first stab at extending BFT to this larger class of systems. We focus on multi-robot systems (MRS), an emerging technology that is increasingly being deployed for applications such as target tracking, warehouse logistics, and exploration. An MRS can consist of dozens of interacting robots and is thus a bona-fide distributed system. The classic masking guarantee is not practical in a MRS, but weproposeavariant called bounded-time interaction that can be implemented, and we present an algorithm that achieves it, in combination with a few small hardware tweaks. We
built a simulator and prototyped wheeled robots to show that our algorithm is effective, and that it has a reasonable overhead.
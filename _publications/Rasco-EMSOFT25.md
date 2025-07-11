---
title: "Rasco: Resource Allocation and Scheduling Co-design for DAG Applications on Multicore"
collection: publications
permalink: /publication/Rasco-EMSOFT25/
excerpt: ''
date: 2025-09-28
venue: 'The ACM SIGBED International Conference on Embedded Software (EMSOFT)'
status: 'To appear at'
paperurl: '.'
authors: 'Abigail Eisenklam, Robert Gifford, Georgiy A. Bondar, <b>Yifan Cai</b>, Tushar Sial, Linh Thi Xuan Phan, and Abhishek Halder'
---

### Authors 

Abigail Eisenklam, Robert Gifford, Georgiy A. Bondar, **Yifan Cai**, Tushar Sial, Linh Thi Xuan Phan, and Abhishek Halder

### Abstract 

As multicore hardware becomes increasingly prevalent in real-time embedded systems, traditional scheduling techniques that assume a single worst-case execution time for each task are no longer adequate, as they fail to account for the impact of shared resources—such as cache and memory bandwidth—on execution time. When tasks execute concurrently on different cores, their execution times can vary substantially with their allocated resources. Moreover, the instruction rate of a task during a job execution varies with time, and this variation pattern differs across tasks. Therefore, to improve performance it is crucial to incorporate the relationship between the resource budget allocated to each task and its time-varying instruction rate in task modeling, resource allocation, and scheduling algorithm design. Yet, no prior work has considered the fine-grained dynamic resource allocation and scheduling problems jointly while also providing hard real-time guarantees. In this paper, we introduce a resource-dependent multi-phase timing model that captures the time-varying instruction rates of a task under different resource allocations and that enables worst-case analysis under dynamic allocation. We present a method for constructing estimates of such a model based on task execution profiles, which can be obtained through measurements. Leveraging these models, we present Rasco, a co-design technique for multicore resource allocation and scheduling of real-time DAG applications with end-to-end deadlines. Rasco leverages the resource-dependent multi-phase model of each task to simultaneously allocate resources at a fine granularity and assign deadlines to tasks to maximize execution progress under resource constraints, all while providing hard real-time schedulability guarantees. Our evaluation results show that Rasco substantially enhances schedulability and reduces end-to-end latency compared to the state of the art.
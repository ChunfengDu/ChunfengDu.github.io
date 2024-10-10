---
title: "[CCF-B] CAGC: A Content-aware Garbage Collection Scheme for Ultra-Low Latency Flash-based SSDs"
collection: publications
category: conferences
permalink: /publication/IEEE-IPDPS 2021
excerpt: ' '
date: 2021-06-28
venue: 'IEEE IPDPS'
# slidesurl: 'https://github.com/ChunfengDu'
paperurl: 'http://academicpages.github.io/files/paper3.pdf'
citation: 'Suzhen Wu, Chunfeng Du, Haijun Li, Hong Jiang, Zhirong Shen, and Bo Mao. CAGC: A Content-aware Garbage Collection Scheme for Ultra-Low Latency Flash-based SSDs. In Proceedings of 35th IEEE International Parallel & Distributed Processing Symposium (IPDPS’21), Virtual Conference, May 17-21, 2021.'
---

With the advent of new flash-based memory technologies with ultra-low latency, directly applying inline data deduplication in flash-based storage devices can degrade the system performance since key deduplication operations lie on the shortened critical write path of such devices. To address the problem, we propose a Content-Aware Garbage Collection scheme (CAGC), which embeds the data deduplication into the data movement workflow of the Garbage Collection (GC) process in ultra-low latency flash-based SSDs. By parallelizing the operations of valid data pages migration, hash computing and flash block erase, the deduplication-induced performance overhead is alleviated and redundant page writes during the GC period are eliminated. To further reduce data writes and write amplification during GC, CAGC separates and stores data pages in different regions based on their reference counts. The performance evaluation of our CAGC prototype implemented in FlashSim shows that CAGC significantly reduces the number of flash blocks erased and data pages migrated during GC, leading to improved user I/O performance and reliability of ultra-low latency flash-based SSDs.

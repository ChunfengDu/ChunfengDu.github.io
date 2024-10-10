---
title: "[CCF-B] LodgeTree: A Last-Level Distributed and Surrogate Buffer Tree for Non-Volatile Memories"
collection: publications
category: conferences
permalink: /publication/IEEE-MSST 2024
excerpt: ' '
date: 2026-06-05
venue: 'IEEE-MSST'
# slidesurl: 'https://github.com/ChunfengDu'
paperurl: 'http://academicpages.github.io/files/paper3.pdf'
citation: ' '
---

Although the emergence of Non-Volatile Memory Techniques (NVMs) offers new insights into solving the problem of memory shortage, tree-based indexing systems face performance overhead when applied to the NVM due to the performance difference between DRAM and NVM. The utilization of buffer techniques exploiting DRAM can alleviate system performance overhead. However, when directly applied to the tree-based index system, it faces some challenges, such as high memory overhead, high flush overhead, and complicated log management. Meanwhile, NVM has some unique features, e.g., asymmetrical read/write, higher random read, and differential access granularity, that should also be carefully focused on in the design. Consequently, we propose LodgeTree, a last-level distributed and surrogate buffer tree design in B+-Tree- based index system. Specifically, LodgeTree fully utilizes the free space situation in the last level of internal nodes of B+ Tree to build a dynamic buffer and proposes three new techniques, including Leaf-count Flush, Hotness-Aware Multiply Split, and Partitioned Version Log, to reduce the memory space overhead, refresh overhead, and log management overhead, and to improve the system performance. Experimental evaluations show that LodgeTree can achieve up to 7.4 × and 1.7 × on average compared with other schemes in system throughput.

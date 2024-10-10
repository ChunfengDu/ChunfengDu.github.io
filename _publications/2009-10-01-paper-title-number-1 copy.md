---
title: "[ACM TOS 2024] FSDedup: Feature-Aware and Selective Deduplication for Improving Performance of Encrypted Non-Volatile Main Memory (CCF-A)"
collection: publications
category: Journal
permalink: /publication/2009-10-01-paper-title-number-1
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
excerpt: ' '
date: 2024-08-06
venue: 'Journal 1'
slidesurl: 'https://github.com/ChunfengDu'
paperurl: 'http://academicpages.github.io/files/FSDedup(TOS2024).pdf'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
# citation: 'Chunfeng Du, Zihang Lin, Suzhen Wu, Yifei Chen, Jiapeng Wu, Shengzhe Wang, Weichun Wang, Qingfeng Wu, and Bo Mao. FSDedup: Feature-Aware and Selective Deduplication for Improving Performance of Encrypted Non-Volatile Main Memory. ACM Transcations Storage, 20(4):1-33, Aug. 2024.'
citation: ' '
---

Enhancing the endurance, performance, and energy efficiency of encrypted Non-Volatile Main Memory (NVMM) can be achieved by minimizing written data through inline deduplication. However, existing approaches applying inline deduplication to encrypted NVMM suffer from substantial performance degradation due to high computing, memory footprint, and index-lookup overhead to generate, store, and query the cryptographic hash (fingerprint). In the preliminary ESD, we proposed the Error Correcting Code (ECC) assisted selective deduplication scheme, utilizing the ECC information as a fingerprint to identify similar data effectively and then leveraging the selective deduplication technique to eliminate a large amount of redundant data with high reference counts. In this article, we proposed FSDedup. Compared with ESD, FSDedup could leverage the prefetch cache to reduce the read overhead during similarity comparison and utilize the cache refresh mechanism to identify further and eliminate more redundant data. Extensive experimental evaluations demonstrate that FSDedup can enhance the performance of the NVMM system further than the ESD. Experimental results show that FSDedup can improve both write and read speed by up to 1.8×, enhance Instructions Per Cycle by up to 1.5×, and reduce energy consumption by up to 2.0×, compared to ESD.

---
title: "[CCF-A] ESD: An ECC-assisted and Selective Deduplication for Encrypted Non-Volatile Main Memory"
collection: publications
category: conferences
permalink: /publication/IEEE-HPCA 2023
excerpt: ' '
date: 2023-03-24
venue: 'IEEE HPCA'
# slidesurl: 'https://github.com/ChunfengDu'
paperurl: 'http://academicpages.github.io/files/paper3.pdf'
citation: 'Chunfeng Du, Suzhen Wu, Jiapeng Wu, Bo Mao, and Shengzhe Wang. ESD: An ECC-assisted and Selective Deduplication for Non-Volatile Main Memory. In Proceedings of the 29th IEEE International Symposium on High-Performance Computer Architecture (HPCA’23), Montreal, QC, Canada, February 25–March 01, 2023.'
---

Reducing write data to encrypted Non-Volatile Main Memory (NVMM) can directly improve NVMM’s endurance, performance, and energy efficiency. However, existing works that straightforwardly apply inline deduplication on encrypted NVMM can significantly lead to system performance degradation due to high computing, memory footprint, and index-lookup overhead to generate, store, and query the cryptographic hash (fingerprint). This paper proposes ESD, an ECC-assisted and Selective Deduplication for encrypted NVMM by exploiting both the device characteristics (ECC mechanism) and the workload characteristics (content locality). First, ESD utilizes the ECC information associated with each cache line evicted from the Last-Level Cache (LLC) as the fingerprint to identify data similarity and avoids the costly hash calculating overhead on the non-duplicate cache lines. Second, ESD leverages selective deduplication to exploit the content locality within cache lines by only storing the fingerprints with high reference counts in the memory cache to reduce the memory space overhead and avoid fingerprints NVMM_lookup operations. The experimental results show that ESD can significantly speed up the writes by up to 3.4x, 4.3x, and 2.6x, speed up the reads by up to 5.3x, 5.0x, and 2.0x, and reduce the energy consumption by up to 96.3%, 96.2%, and 56.6% than Baseline, Dedup SHA1, and DeWrite, respectively. Meanwhile, ESD also can significantly outperform other schemes in tail latency.

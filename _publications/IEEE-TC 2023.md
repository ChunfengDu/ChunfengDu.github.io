---
title: "[CCF-A] EaD:ECC-Assisted Deduplication With High Performance and Low Memory Overhead for Ultra-Low Latency Flash Storage"
collection: publications
category: Journal
permalink: /publication/IEEE-TC 2023
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
excerpt: ' '
date: 2023-01-01
venue: 'IEEE-TC'
# slidesurl: 'https://github.com/ChunfengDu'
paperurl: 'http://academicpages.github.io/files/FSDedup(TOS2024).pdf'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
# citation: 'Chunfeng Du, Zihang Lin, Suzhen Wu, Yifei Chen, Jiapeng Wu, Shengzhe Wang, Weichun Wang, Qingfeng Wu, and Bo Mao. FSDedup: Feature-Aware and Selective Deduplication for Improving Performance of Encrypted Non-Volatile Main Memory. ACM Transcations Storage, 20(4):1-33, Aug. 2024.'
citation: ' '
---

Data deduplication has become a commodity feature in flash storage products to effectively reduce redundant write data and improve space efficiency. However, it also introduces computing and memory overhead to generate and store the cryptographic hash (fingerprint) in face of the moderate data redundancy in primary storage. With the advent of 3D XPoint and Z-NAND technologies, and the stronger cryptographic hash functions in use, such as SHA-256, both the computing and memory overheads are increasingly serious performance bottlenecks for inline data deduplication in these ultra-low latency flash storage. To address these problems, we propose an ECC-assisted Deduplication approach, called EaD, which exploits the ECC property and the asymmetric read-write performance characteristics of modern flash storage. EaD first identifies data similarity by leveraging the device-generated ECC values of data chunks as their fingerprints, significantly reducing the costly MD5/SHA-based cryptographic hash computing and alleviating the memory space overhead. Based on the identification results, similar data chunks and their ECCs are read from the flash to perform a byte-by-byte comparison in memory to definitively identify and remove redundant data chunks. Our experiments show that the EaD approach significantly increases I/O performance by up to 4.2 × , with an average of 2.5 × , compared with the existing MD5/SHA- and sampling-based deduplication approaches.

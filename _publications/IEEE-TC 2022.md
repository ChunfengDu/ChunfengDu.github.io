---
title: "[CCF-A] DedupHR: Exploiting Content Locality to Alleviate Read/Write Interference in Deduplication-Based Flash Storage"
collection: publications
category: Journal
permalink: /publication/IEEE-TC 2022
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
excerpt: ' '
date: 2022-06-01
venue: 'IEEE-TC'
# slidesurl: 'https://github.com/ChunfengDu'
paperurl: 'http://academicpages.github.io/files/FSDedup(TOS2024).pdf'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
# citation: 'Chunfeng Du, Zihang Lin, Suzhen Wu, Yifei Chen, Jiapeng Wu, Shengzhe Wang, Weichun Wang, Qingfeng Wu, and Bo Mao. FSDedup: Feature-Aware and Selective Deduplication for Improving Performance of Encrypted Non-Volatile Main Memory. ACM Transcations Storage, 20(4):1-33, Aug. 2024.'
citation: ' '
---

Data deduplication has been widely employed in flash-based storage as an effective technique for enhancing reliability and cost efficiency. However, the read/write interference problem of flash storage, where on-going write requests prevent read requests from accessing available data and significantly increase read latency, remains a critical concern with the rapid evolutions of flash chips from SLC through MLC to TLC and on to QLC, with PLC on the horizon, especially under workloads with a mixture of read and write requests. To significantly improve the read performance in face of read/write interference, which is often more critical than the write performance, we propose an enhanced Hot Read Data Replication scheme for deduplication-based flash storage, called DedupHR, to alleviate the read/write interference problem. DedupHR exploits the content locality in the deduplication-based flash storage and outsources the data blocks with high reference count to a surrogate space such as a dedicated spare flash chip or an over-provisioned space in an SSD. By servicing some conflicted read requests on the surrogate flash space, DedupHR can significantly alleviate, if not entirely eliminate, the contention between the read requests and the on-going write requests. The evaluation results show that DedupHR significantly improves the state-of-the-art schemes in terms of the system performance and cost efficiency. Consequently, the tail-latency of the deduplication-based flash storage is also reduced.

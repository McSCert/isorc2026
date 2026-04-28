---
name: "Slowdown Modeling under Interference in Spatially Partitioned GPUs"
speakers:
  - 
track: Research
tags: 
  - Research Paper
---
Abstract
--------
GPUs are widely used in embedded and cyber-physical systems to accelerate compute‑intensive workloads, but their shared-memory design makes timing predictability challenging. Spatial partitioning of Streaming Multiprocessors (SMs) allows concurrent execution of multiple workloads, yet interference in shared resources such as the L2 cache and DRAM can still cause significant slowdown.
This paper introduces a three‑stage framework that models interference‑aware slowdown in spatially partitioned GPU systems using observable execution behavior and software‑only techniques. The first stage models solo GPU kernel execution time as a function of allocated SMs. The second stage provides a lightweight peer‑specific interference model that uses normalized resource‑pressure ratios. The third stage employs a learning‑based model to predict slowdown across peers and partition configurations.
We evaluate the framework on representative GPU kernels and multiple SM partitions on a commodity GPU. The peer‑specific model achieves an average prediction error of about 8%--9%. The learning‑based model reduces the error across partition configurations to about 6%. When predicting slowdown for  GPU kernels not included during training, a single global model yields about 14.5% error on average, while a similarity‑based predictor lowers this to about 10% when a close match is available, illustrating a trade‑off between predictability and generality.

Authors
-------
1. Sahar Mobaiyen <sahar.mobaiyen@mdu.se> (Mälardalen University, Sweden)
2. Mikael Sjödin <mikael.sjodin@mdu.se> (Mälardalen University, Sweden)
3. Saad Mubeen <saad.mubeen@mdu.se> (Mälardalen University, Sweden)
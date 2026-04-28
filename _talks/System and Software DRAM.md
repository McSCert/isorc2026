---
name: "DRAM Bank-Aware Memory Allocation for Embedded Real-Time Virtualization"
speakers:
  - 
track: Research
tags: 
  - Research Paper
---
Abstract
--------
Shared-memory interference is a major source of timing variability in modern multicore embedded systems that require high timing predictability. In DRAM-based platforms, concurrent accesses that compete on the same bank can trigger row-buffer conflicts, increasing memory latency.

To improve timing isolation and predictability, bank partitioning has established as a key technique to support the co-existence of multiple virtual machines with mixed safety and security requirements on a shared hardware platform. Beyond timing predictability, it also provides security-hardening effects by reducing vulnerability to contention-based denial-of-service and row-buffer timing-channel attacks.

This paper presents a DRAM bank-aware memory allocation approach for embedded virtualization, combining a hypervisor-level mechanism for bank-aware page placement with a practical methodology to identify the physical address bits used for DRAM bank selection. We instantiate and evaluate the approach in the lightweight Bao hypervisor on the Raspberry Pi 4 embedded platform.

Experimental results with memory-intensive benchmarks show that forcing VMs to share the same DRAM bank set causes severe slowdowns, up to 85.3% relative to the default Bao allocator. In contrast, bank-aware allocation limits the degradation to about 20.4% across workloads.

Authors
-------
1. Eduardo Bischoff Grasel <eduardobgrasel@gmail.com> (Federal University of Santa Catarina)
2. Giovani Gracioli <giovani@lisha.ufsc.br> (Federal University of Santa Catarina)
3. Daniel Casini <daniel.casini@santannapisa.it> (Scuola Superiore Sant'Anna, Italy)
---
name: "SlimFlit: A simple Network-on-Chip for Real-Time Systems"
speakers:
  - 
track: Research
tags: 
  - Research Paper
---

Abstract
--------
Time-predictable on-chip communication is crucial for real-time multi-core systems. 
While conventional best-effort NoC designs optimize average-case performance, resulting in pessimistic worst-case performance bounds, NoCs for real-time systems are purpose-built to provide tighter bounds but often come at the cost of low resource utilization.
In this paper, we present SlimFlit, a minimalistic best-effort NoC architecture, and show that we can derive worst-case traversal time bounds for it.

SlimFlit minimizes hardware resources by using single-flit packets and simple dimension-order routing in a mesh topology. The NoC achieves time predictability through a simple router design with input buffering, no virtual channels, and round-robin arbitration, enabling the computation of worst-case traversal times. To reduce pessimism in the latency bounds, we introduce rate control at the network interfaces and provide an analysis for different communication patterns. 

We evaluate SlimFlit by deriving its worst-case traversal-time bound theoretically for a 4 x 4 network and by exploring its average-case performance through simulation with synthetic traffic patterns. 
While the results show that the theoretical worst-case bounds are pessimistic, SlimFlit offers an interesting design point for real-time NoCs and demonstrates that time predictability does not necessarily require specialized scheduling and flow-control mechanisms.

Authors
-------
1. Tjark Petersen <tjape@dtu.dk> (Technical University of Denmark)
2. Voica Maria Gavrilut <voga@dtu.dk> (Technical University of Denmark)
3. Luca Pezzarossa <lpez@dtu.dk> (Technical University of Denmark)
4. Martin Schoeberl <masca@dtu.dk> (Technical University of Denmark)
---
name: "Trace-Aware Multidimensional Analysis of Hidden Bottlenecks in Autoscaling Microservices"
speakers:
  - 
track: Research
tags: 
  - Research Paper
---
Abstract
--------
Autoscaling microservice-based applications remains challenging due to complex service dependencies and dynamic workload compositions. Existing autoscalers primarily rely on local resource metrics or latency thresholds, which often fail to identify bottlenecks that emerge indirectly through fan-out amplification along service chains. As a result, hidden bottlenecks may degrade end-to-end performance without triggering appropriate scaling actions. In this paper, we propose a trace-aware, multi-dimensional bottleneck detection framework that leverages distributed tracing data to quantify each microservice’s contribution to end-to-end latency and performance degradation. Our approach integrates structural information from service interactions with statistical and causal indicators to identify bottlenecks that are invisible to metric-based and root-cause-analysis (RCA) techniques. We evaluate the proposed framework using a Kubernetes-based microservice application under realistic and dynamically composed workloads. Experimental results demonstrate that our approach significantly improves autoscaling effectiveness under hidden bottleneck scenarios compared to metric-driven and RCA-assisted baselines. We further analyze the impact of combining trace-aware inference with RCA and show that the two provide complementary benefits under certain workload conditions. These results highlight the importance of trace-level visibility as an architectural primitive for adaptive autoscaling and motivate further exploration of trace-informed mechanisms for next-generation critical real-time and distributed systems.

Authors
-------
1. Majid Dashtbani <mdashtba@uwaterloo.ca> (University of Waterloo)
2. Ladan Tahvildari <ladan.tahvildari@uwaterloo.ca> (University of Waterloo)
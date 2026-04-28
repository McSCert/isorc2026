---
name: "Power-Performance Trade-offs using Offline Reinforcement Learning for Compute Workloads"
speakers:
  - 
track: Research
tags: 
  - Research Paper
---
Abstract
--------
Modern hosting platforms for compute-intensive workloads, such as in AI/ML and high performance computing, must deliver assured performance to the applications while keeping operational energy costs low. Built-in power sensing and actuation capabilities in modern CPUs enable system  software to monitor and adapt energy consumption at runtime. While reinforcement learning (RL) is a natural fit for such control problems, online training faces challenges including inadequate simulation fidelity, runtime perturbations, and system reliability concerns. To overcome these challenges, we explore offline reinforcement learning as an alternative for designing an autonomous CPU power controller that improves energy efficiency without unduly degrading application performance. Offline RL leverages datasets of prior state transitions collected from arbitrary policies, thereby avoiding the risks of online exploration.  Our methodology applies offline RL in a gray-box energy optimization framework, combining application-agnostic performance signals (e.g., heartbeats) with hardware performance counters. By evaluating compute-bound and memory-bound benchmarks on live systems using Intel Running Average Power Limit (RAPL), we demonstrate substantial energy reductions at acceptable performance.

Authors
-------
1. Akhilesh Raj <akhilesh.raj@vanderbilt.edu> (Vanderbilt University)
2. Swann Perarnau <swann@anl.gov> (Argonne National Laboratory)
3. Solomon Abera Bekele <sbekele@anl.gov> (Argonne National Laboratory)
4. Aniruddha Gokhale <a.gokhale@vanderbilt.edu> (Vanderbilt University, USA)
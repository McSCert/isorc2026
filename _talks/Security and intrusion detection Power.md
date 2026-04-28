---
name: "Power-Based Security Monitoring: Non-Invasive Detection of Task Execution Violations in Real-Time Systems"
speakers:
  - 
track: Research
tags: 
  - Research Paper
---
Abstract
--------
Modern safety-critical systems, from centralized automotive Electrical/Electronic (E/E) architectures to distributed cyber-physical deployments, are increasingly reliant on Real-Time Operating Systems (RTOSs) to guarantee timing determinism. However, these systems face growing security threats
where attackers can subvert traditional defense methods to mask malicious activity. This paper presents Power-Based Schedule Verification (PBSV), a novel, non-invasive security monitoring
methodology that detects task execution violations, specifically, task overruns and underruns through power consumption side-channels.

Unlike invasive software monitors that share the attack surface with the target, our approach utilizes an out-of-band side-channel monitor to establish a trust anchor grounded in physical energy consumption. We introduce an algorithm that reconstructs the runtime schedule from raw power traces, leveraging the distinct RTOS idle state as ground-truth anchor. This is compared against a formal Workload Specification defining the Best Case Execution Time (BCET) and Worst Case Execution Time (WCET). This methodology was validated on an STM32 Microcontroller, and
our framework successfully detects timing violations indicative of logic bypasses or unauthorized code execution, demonstrating a robust ”correctness-by-observation” mechanism.

Authors
-------
1. Mayukh Haldar <mhaldar@uwaterloo.ca> (University of Waterloo)
2. Jenish Patel <j347pate@uwaterloo.ca> (University of Waterloo)
3. Sebastian Fischmeister <sfischme@uwaterloo.ca> (University of Waterloo)
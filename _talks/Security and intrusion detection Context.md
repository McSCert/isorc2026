---
name: "A Context-Aware Trust Management and Calibration Framework for Cyber-Physical Systems"
speakers:
  - 
track: Research
tags: 
  - Research Paper
---
Abstract
--------
This paper demonstrates a closed-loop framework that addresses a critical gap in autonomous systems: the lack of a formal process for trust repair. Current trust management systems are often inadequate, lacking both context-awareness and a mechanism for an agent to recover from faults. Our framework integrates Signal Temporal Logic (STL) for context-aware runtime verification and Subjective Logic (SL) to quantify trust as a formal opinion that incorporates uncertainty. When trust degrades, a novel Temporary Calibration Assignment (TCA) mechanism uses Model Predictive Control (MPC) to generate a safe and achievable challenge. This challenge creates a structured path for the agent to prove its reliability has been restored. Evaluation in Simulation of Urban MObility (SUMO) confirms the framework’s effectiveness. The system successfully detects behavioral violations, lowers the corresponding trust opinion, and, upon issuing a Temporary Calibration Assignment (TCA), correctly differentiates between compliant agents, whose trust is repaired, and non-compliant agents, whose trust continues to decline. This research introduces a formal trust calibration and repair process, enabling more resilient and explainable autonomous systems capable of earning and maintaining trust.

Authors
-------
1. Waleed Khan <wqkhan@uwaterloo.ca> (University of Waterloo)
2. Sebastian Fischmeister <sebastian.fischmeister@uwaterloo.ca> (University of Waterloo)
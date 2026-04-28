---
name: "Hard Real-Time Embedded Implementation of Closed-Loop Gastric Pacemaker"
speakers:
  - 
track: Research
tags: 
  - Research Paper
---
Abstract
--------
Gastrointestinal motility disorders, such as gastroparesis, significantly impair patient quality of life, yet current treatment options like open-loop gastric electrical stimulation (GES) offer limited efficacy. While recent research has proposed closed-loop pacing strategies, existing implementations rely heavily on high-level software or general-purpose embedded platforms. These systems operate in soft real-time, lacking the temporal determinism and verifiable timing guarantees required for safety-critical medical certification. This paper presents the first hard real-time, bare-metal implementation of a closed-loop gastric pacemaker on a precision-timed processor architecture. We utilize a Hardware-in-the-Loop (HiL) framework to validate the system against a high-fidelity computational gastric model. Results demonstrate that the pacemaker successfully detects and corrects distinct dysrhythmic propagation patterns. Furthermore, static Worst-Case Execution Time (WCET) analysis establishes a deterministic execution bound, providing a verified timing envelope that eliminates unpredictable execution latencies. This work provides a technical foundation for future development of certifiable, standalone closed-loop gastric bioelectronic systems.

Authors
-------
1. HyungJoo Eugene Lee <hlee875@aucklanduni.ac.nz> (University of Auckland)
2. Avinash Malik <avinash.malik@auckland.ac.nz> (University of Auckland)
3. Partha Roop <p.roop@auckland.ac.nz> (University of Auckland, New Zealand)
4. Nathan Allen <nathan.allen@aut.ac.nz> (Auckland University of Technology, New Zealand)
5. Daniel Martinez <dmar256@aucklanduni.ac.nz> (University of Auckland)
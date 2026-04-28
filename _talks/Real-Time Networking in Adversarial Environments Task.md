---
name: "Task Splitting to Mitigate Schedule-Based Anterior Attacks in Real-Time Embedded Systems"
speakers:
  - 
track: Research
tags: 
  - Short Paper
---
Abstract
--------
In real-time embedded systems, schedule-based attacks (SBAs) are often used by adversaries to exploit predictable execution orders in order to cause instability, steal information, and/or alter input/output data. While existing work focused mostly on posterior attacks where the adversary manipulatse output data, anterior attacks that target  input data remain relatively unexplored. In this paper, we investigate the combined impact of priority assignment and task splitting to mitigate anterior attacks in real-time embedded systems. We show that through task splitting, it is possible to assign the vulnerable sub-tasks  a high priority, thereby ensuring both schedulability and improved protection from anterior attacks. Extensive simulation-based evaluations demonstrate that the proposed approach significantly reduces anterior attack opportunities compared to baseline real-time scheduling algorithms, with modest scheduling overhead.

Authors
-------
1. Sina Y. Karin <syarikar@gmu.edu> (George Mason University)
2. Hakan Aydin <aydin@gmu.edu> (George Mason University)
3. Dakai Zhu <dakai.zhu@utsa.edu> (University of Texas at San Antonio, USA)
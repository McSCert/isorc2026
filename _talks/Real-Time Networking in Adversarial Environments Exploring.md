---
name: "Exploring and Exploiting Synchrony Limitations of Time-Triggered Network-Agnostic Guardians"
speakers:
  - 
track: Research
tags: 
  - Research Paper
---
Abstract
--------
Time-triggered communication protocols rely on trusted components known as guardians to enforce adherence to predetermined network schedules. Network-agnostic guardians offer an efficient and scalable distributed solution with reduced implementation cost and complexity compared to network‑aware alternatives. However, this efficiency is based on the guardian’s dependence on the controlled node for clock synchronization, which introduces a vulnerability: a malicious node can exploit this dependency to launch timing attacks against its guardian and eventually interfere with messages from other nodes on the network.

In this paper, we establish a theoretical lower bound on the attainable clock synchronization precision between a node and its network-agnostic guardian. Building on this result, we introduce a timing attack that leverages the unavoidably imperfect clock synchrony to cause controlled and undetected de-synchronization of the guardian. The attack enables a malicious node to cause collisions with targeted critical network messages. We evaluate the effectiveness of the attack using a FlexRay field bus network model implemented in the OMNeT++ simulation framework. Our results show that the attack is able to remain undetected with 100% success and disrupts the transmission of the critical messages of the target node by causing collisions with them with 100% success.

Authors
-------
1. Shreya Vithal Kulhalli <kulhalli@rptu.de> (RPTU Kaiserslautern-Landau)
2. Mohammad Ibrahim Alkoudsi <alkoudsi@rptu.de> (RPTU Kaiserslautern-Landau)
3. Gerhard Fohler <fohler@rptu.de> (RPTU Kaiserslautern-Landau)
---
name: "Towards a Fully Verified Artificial DNA - Formal Verification of Building Block Behavior"
speakers:
  - 
track: Research
tags: 
  - Research Paper
---
Abstract
--------
The development of safety-critical distributed embedded systems requires that such systems operate reliably and remain resilient in the presence of faults. The Artificial Hormone System (AHS) provides a middleware architecture for distributed embedded real-time systems, making them self-organizing, decentralized, and self-healing. These properties are achieved through the hormone control loop of the AHS, where processing units use only messages—the so-called hormones—to coordinate the allocation of the system’s tasks without relying on a central decision-making entity. As a result, the system can tolerate the loss of computational nodes as well as performance degradation in non-critical or less critical tasks.

The AHS is complemented by the Artificial DNA (ADNA), which specifies the tasks to be distributed, their interdependencies, and their parameterizations. The ADNA is based on the observation that only a limited set of fundamental building blocks—such as timers, arithmetic logic units (ALUs), PID controllers, and filters—is required to represent the functionality of embedded systems. While the safety and overall reliability of the AHS and ADNA mechanisms have been extensively studied, the reliability of the individual building blocks themselves has largely not been considered in isolation.

With this paper, we aim to address this gap by formally verifying the correctness and reliability of selected commonly used building blocks. Since AHS and ADNA are primarily applied in real-time systems with time-critical behavior, it is necessary to verify not only their logical correctness but also their temporal correctness. For this purpose, the model-checking tool UPPAAL was chosen, as its timed automata framework is well suited for verifying behavioral invariants as well as timing properties. We present the fundamentals of verifying basic building blocks using UPPAAL, as well as the limitations of this verification process. We also provide key verification results for selected components whose behavior was found to be less reliable than expected.

Authors
-------
1. Aleksey Koschowoj <koschowoj@es.cs.uni-frankfurt.de> (Goethe University Frankfurt am Main, Germany)
2. Thomas Zander <s6683525@stud.uni-frankfurt.de> (Goethe University Frankfurt am Main, Germany)
3. Margareta Scheffer <s6743003@stud.uni-frankfurt.de> (Goethe University Frankfurt am Main, Germany)
4. Timo Kisselbach <kisselbach@em.uni-frankfurt.de> (Goethe University Frankfurt am Main, Germany)
5. Mathias Pacher <mathias.pacher@dhbw-karlsruhe.de> (DHBW Karlsruhe, Germany)

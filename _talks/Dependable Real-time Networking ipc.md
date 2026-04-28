---
name: "ipc_shared_ptr: A Publish/Subscribe-Aware Smart Pointer for Cross-Process Object Lifetime Management"
speakers:
  - 
track: Research
tags: 
  - Research Paper
---
Abstract
--------
True zero-copy Inter-Process Communication (IPC) in publish/subscribe (pub/sub) middleware such as Robot Operating System 2 (ROS 2) requires subscribers to reference message objects in publisher-owned shared memory. Objects must not be reclaimed while referenced, yet must eventually be reclaimed, with correct handling of crash recovery and Transient Local QoS retention requirements. We propose ipc_shared_ptr, a pub/sub-aware smart pointer for cross-process message lifetime management. ipc_shared_ptr exploits pub/sub structural
properties to specialize Birrell’s reference listing, limiting global metadata updates to per-subscriber 0↔1 transitions and achieving an order-of-magnitude reduction in global communication over general-purpose distributed reference counting. We analyze the key metadata management tradeoff: scalability versus implementation simplicity. Owner-driven reclaim offers greater scalability, but concurrent membership changes and reclamation
decisions produce races that widen the correctness-verification state space. Single-writer achieves structural atomicity, eliminating this complexity at the cost of a centralized bottleneck.
iceoryx2 (owner-driven reclaim) and Agnocast — a true zero-copy ROS 2 IPC middleware sharing the publisher’s heap with subscribers and adopting ipc_shared_ptr with single-writer —
embody each architecture. Comparative evaluation at the scale of Autoware — the largest open-source ROS 2 application — confirms that single-writer achieves sufficient scalability: at 200
topics, two subscribers per topic and 100 Hz, Agnocast’s E2E p99 is over 5× lower than iceoryx2’s, justifying implementation simplicity over owner-driven reclaim.

Authors
-------
1. Takahiro Ishikawa-Aso <takahiro.ishikawa@pf.is.s.u-tokyo.ac.jp> (The University of Tokyo)
2. Atsushi Yano <yano.a.112@ms.saitama-u.ac.jp> (Saitama University)
3. Koichi Imai <koichi.imai.2@tier4.jp> (TIER IV, inc.)
4. Takuya Azumi <takuya@mail.saitama-u.ac.jp> (Saitama University)
5. Shinpei Kato <shinpei@pf.is.s.u-tokyo.ac.jp> (University of Tokyo)
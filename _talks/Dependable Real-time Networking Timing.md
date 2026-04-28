---
name: "Timing‑Aware Configuration Framework for TSN and OPC~UA in Industrial Automation"
speakers:
  - 
track: Research
tags: 
  - Research Paper
---
Abstract
--------
The convergence of OPC UA Publish–Subscribe (PubSub) and Time-Sensitive Networking (TSN) enables vendor-agnostic and predictable communication in real-time distributed industrial automation systems.
Deploying such systems, however, requires consistent configuration across application and network layers that currently expose mismatched timing abstractions. TSN depends on precise traffic specifications, while OPC UA PubSub provides extensive configuration options without guidance on selecting timing-related parameters, creating engineering complexity and increasing commissioning effort. 
To address this challenge, this paper presents TPConf, a tool-supported framework that co-configures OPC UA PubSub and TSN from traffic specifications by classifying application requirements into industrial automation traffic classes, mapping them to TSN classes (ST, AVB, BE), and deriving corresponding PubSub parameters. TPConf further generates ready-to-compile publisher code for open62541, and an industrial use case with diverse simulated flows demonstrates the automated co-configuration workflow. By unifying application and network configuration, TPConf reduces engineering effort and supports predictable and scalable OPC UA over TSN deployments in real-time automation systems.

Authors
-------
1. Kasra Ekrad <kasra.ekrad@mdu.se> (Department of Network and Embedded Systems, Mälardalen University, Västerås, Sweden)
2. Bjarne Johansson <bjarne.johansson@se.abb.com> (ABB)
3. Inés Alvarez Vadillo <ines.alvarez-vadillo@se.abb.com> (ABB)
4. Saad Mubeen <saad.mubeen@mdu.se> (Mälardalen University, Sweden)
5. Mohammad Ashjaei <mohammad.ashjaei@mdu.se> (Mälardalen University)
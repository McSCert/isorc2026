---
name: "Cross-MAC IDS for Denial-of-Sleep Detection in Wireless Sensor Networks"
speakers:
  - 
track: Research
tags: 
  - Research Paper
---
Abstract
--------
Wireless Sensor Networks (WSNs) increasingly rely on energy-saving mechanisms such as duty cycling and adaptive power control to extend network lifetime. This trend enables the deployment of large-scale, high-density IoT infrastructures in smart-city and massive-IoT settings. However, dense deployments also amplify threats targeting energy availability, where adversaries can degrade network operation by forcing devices to waste power through repeated channel activity and packet processing. In this context, MAC-layer attacks are particularly critical because many WSN applications enforce security primarily at higher layers, allowing malicious traffic to trigger energy-consuming operations before being filtered.

Among energy-depletion threats, Denial-of-Sleep (DoSl) attacks aim to keep nodes awake when they should be sleeping, rapidly draining batteries and reducing network lifetime. In this paper, we introduce an OMNeT++ module that models sensor-node energy dynamics through seven power states and supports the simulation of three representative DoSL strategies, enabling systematic evaluation under energy-exhaustion conditions. Building on the simulation data, we then characterize a MAC-layer protocol-agnostic Intrusion Detection System (IDS) based on Machine Learning (ML) for DoSl detection. We benchmark the proposed approach across three MAC designs, using IEEE 802.15.4 as a standards-based baseline and comparing it with representative duty-cycled WSN MAC protocols (B-MAC and X-MAC). Results show that duty-cycled protocols can reduce the impact of DoSL, and IDS can effectively detect DoSL attacks with 93,37% for multiclass and 97,92% for binary classification within a window of 10 seconds.

Authors
-------
1. Davide Amoruso <d.amoruso3@studenti.unisa.it> (University of Salerno, Italy)
2. Biagio Boi <bboi@unisa.it> (University of Salerno, Italy)
3. Christian Esposito <esposito@unisa.it> (University of Salerno, Italy)

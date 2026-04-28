---
name: "Edge Based Predictive Maintenance Using a TinyML Temporal Convolutional Transformer for NASA Turbofan Remaining Useful Life Estimation"
speakers:
  - 
track: Research
tags: 
  - Research Paper
---
Abstract
--------
Predictive maintenance has become a critical component of modern industrial systems where unplanned downtime leads to substantial operational and economic losses. Remaining Useful Life estimation plays a central role in enabling maintenance scheduling based on actual equipment condition rather than predefined service intervals. While deep learning models have demonstrated strong performance on benchmark datasets such as the NASA turbofan engine degradation dataset, their computational requirements typically prevent direct deployment on resource constrained embedded platforms. This work presents an edge deployable predictive maintenance framework based on a compact Temporal Convolutional Transformer architecture tailored for TinyML environments. The proposed model integrates causal dilated temporal convolutions for local degradation pattern extraction with a lightweight self attention mechanism for long range dependency modeling. The architecture is carefully optimized through fake quantization to satisfy the memory and latency constraints of an STM32L4+ microcontroller.
Experiments conducted on the NASA turbofan Remaining Useful Life dataset demonstrate that the proposed approach achieves competitive prediction accuracy compared to conventional recurrent and transformer based methods, while reducing memory footprint and inference latency to fit within microcontroller class hardware. The final quantized model is deployed on an STM32L4+ board using TensorFlow Lite for Microcontrollers, validating real time on device inference. This study demonstrates that advanced sequence modeling for predictive maintenance can be effectively realized at the extreme edge without reliance on cloud computation.

Authors
-------
1. Abdellah Benbelghit <benbelghit.abdellah@gmail.com> (Ecole de Technologie Sup´erieure (´ETS))
2. Abdelouahed Gherbi <abdelouahed.gherbi@etsmtl.ca> (Ecole de Technologie Sup´erieure (´ETS))
3. Pierre-Emmanuel Hladik <pierre-emmanuel.hladik@ls2n.fr> (Nantes Universit´e, ´Ecole Centrale Nantes)
4. Ahmed Bali <ahmed.bali@etsmtl.ca> (Ecole de Technologie Sup´erieure ( ´ETS))
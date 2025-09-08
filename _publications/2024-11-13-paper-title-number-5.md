---
title: "MambaVesselNet++: A Hybrid CNN-Mamba Architecture for Medical Image Segmentation"
collection: publications
category: manuscripts
permalink: /publication/2025-07-15-mambavesselnetpp
excerpt: 'Qing Xu, **Yanming Chen**, Yue Li, Ziyu Liu, Zhenye Lou, Yixuan Zhang, Huizhong Zheng, Xiangjian He'
date: 2025-07-15
venue: 'ACM Transactions on Multimedia Computing, Communications, and Applications (TOMM)'
paperurl: 'https://doi.org/10.1145/3757324'
---

### **Abstract**
Medical image segmentation plays an important role in computer-aided diagnosis. Traditional convolution-based U-shape segmentation architectures are usually limited by the local receptive field. Vision transformers capture global contexts effectively but suffer from high computational costs due to non-linear self-attention. To address this, the selective state space model (SSM) **Mamba** provides efficient modeling of long-range dependencies with linear complexity.  
We propose **MambaVesselNet++**, a Hybrid CNN–Mamba framework for medical image segmentation. It integrates a **Hybrid Image Encoder (Hi-Encoder)**, combining texture-aware convolutional layers for low-level semantics and Mamba modules for global dependency modeling, and a **Bifocal Fusion Decoder (BF-Decoder)** that fuses local and global features via skip connections.  
Extensive experiments demonstrate that MambaVesselNet++ outperforms CNN-, transformer-, and Mamba-based state-of-the-art methods across diverse 2D, 3D, and instance segmentation tasks  [oai_citation:1‡3757324.pdf](file-service://file-1PXYxRmZNJUrzrnXvrrk1W).

### **Key Contributions**
- **Hybrid CNN–Mamba architecture:** Combines CNNs for detailed local and multi-scale feature extraction with Mamba for efficient global dependency modeling.  
- **Adaptive convolution & multi-branch decoding:** Extends applicability from 3D cerebrovascular segmentation to diverse **2D/3D modalities** and supports both **semantic** and **instance** segmentation.  
- **Broad evaluation:** Validated on five external medical modalities (dermoscopy, colonoscopy, fundus, ultrasound, and histopathology), achieving superior performance compared to state-of-the-art baselines  [oai_citation:2‡3757324.pdf](file-service://file-1PXYxRmZNJUrzrnXvrrk1W).
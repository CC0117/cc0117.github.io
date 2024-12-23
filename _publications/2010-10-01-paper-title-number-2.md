---
title: "MambaVesselNet: A Hybrid CNN-Mamba Architecture for 3D Cerebrovascular Segmentation"
collection: publications
category: conferences
permalink: /publication/2024-12-3-mamba-vesselnet
excerpt: '**Yanming Chen**, Ziyu Liu, Xiangjian He'
# date: 2024-12-3
venue: 'ACM Multimedia Asia 2024'
paperurl: '/files/MambaVesselNet.pdf'
# citation: 'Yanming Chen, Ziyu Liu, Xiangjian He. (2024). &quot;MambaVesselNet: A Hybrid CNN-Mamba Architecture for 3D Cerebrovascular Segmentation.&quot; <i>ACM Multimedia Asia 2024</i>.'
---

### **Abstract**
Segmenting vessels in magnetic resonance imaging (MRI) stands as a mainstream approach for evaluating cerebrovascular conditions. Due to the complex semantics and topology of cerebrovascular structures, existing CNN-based segmentation methods often fail to correlate the topological structure and branch vessels, resulting in incomplete segmentation. To address the challenge of global dependencies modeling, transformer architectures have been employed due to their capability of capturing long-range dependencies, and they have shown promise in 3D medical image segmentation. However, the transformer architecture greatly increases the computational burden when processing high-dimensional 3D MRI images. In light of this, a selective state space model (SSM) Mamba has gained recognition for its adeptness in handling long-range dependencies in sequential data, particularly noted for its efficiency and speed in natural language processing applications. Mamba is now widely applied in various computer vision tasks. Based on these findings, in this study, we propose MambaVesselNet, a Hybrid CNN-Mamba network for 3D cerebrovascular segmentation. MambaVesselNet leverages CNNs to capture local features and incorporates the Mamba block at the bottleneck to model long-range dependencies within the whole-volume features. The effectiveness of MambaVesselNet is validated on a public cerebrovascular dataset, and our benchmark demonstrates new state-of-the-art performance.

### **Key Contributions**
- We propose a novel Hybrid CNN-Mamba model (MambaVesselNet) for 3D medical image segmentation. To our knowledge, this is the first study that explored the integration of CNN and Mamba for segmenting cerebrovascular structures in MRA scans.
- Different from other Mamba-based vision models using Mamba as a backbone across different scales, we propose a novel architecture that places the Mamba module at the bottleneck to extract information at the same dimension, reducing computational load while achieving better performance.
- We validate the effectiveness of our proposed model on the public cerebrovascular dataset. MambaVesselNet achieves new state-of-the-art performance.

For more details, download the [paper here](MambaVesselNet.pdf).
# DHA Adapter for Remote Sensing Scene Classification
We propose the Dynamic Heterogeneous Attention (DHA) Adapter, a novel PEFT framework that adaptively models multi-scale remote sensing features via content-aware dynamic routing. As a plug-and-play solution, it enables generic lightweight backbones to achieve performance competitive with or even superior to full fine-tuning while significantly reducing trainable parameters and memory footprint.
!(figures/DHA Adapter.png)
*The architecture of DHA Adapter.*

### 2. Experimental Results
!(figures/result.png)
*Comparison of DHA Adapter with Full Fine-Tuning, LoRA, and Bottleneck Adapters across multiple backbones and datasets.*

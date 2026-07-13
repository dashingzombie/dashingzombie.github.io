---
title: "Scalable Visual Representation Learning"
excerpt: "DINOv2, diffusion, and VQ-VAE benchmarking on 1.5 million images with 18% higher AUROC and 54% lower training cost."
collection: portfolio
---

## Model performance

At the Morgridge Institute for Research, I trained and benchmarked DINOv2, diffusion, and hierarchical VQ-VAE architectures on **1.5 million multi-channel Cell Painting images**. DINOv2 representations increased gene-classification AUROC by **18%** relative to an ImageNet-pretrained baseline.

## Infrastructure performance

I implemented distributed training across **64 A100 GPUs** using DeepSpeed ZeRO-3. The optimized training stack reduced epoch latency from **6.4 hours to 1.7 hours**, delivering **3.8× higher throughput** and **54% lower compute cost**.

I also developed a discrete latent pipeline using VQ-VAE token spaces for conditional diffusion of unseen perturbations and temporal transitions. The project combined architecture benchmarking, multi-node training, performance profiling, and cost optimization.

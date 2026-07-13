---
layout: archive
title: "Resume"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

ML and hardware engineer with end-to-end experience across sensing platforms, robotics, computer vision, distributed training, and data infrastructure. I turn ambiguous measurement problems into validated systems by connecting hardware design, acquisition software, model development, and quantitative evaluation.

[Email](mailto:devd@qgg.au.dk) · [Phone](tel:+16082920740) · [LinkedIn](https://www.linkedin.com/in/dev-mehrotra)

## Core technical skills

- **Hardware and robotics:** sensor integration, device orchestration, camera and illumination control, environmental control, contact microphones, LiDAR, time-of-flight sensors, UR5, ROS, Gazebo
- **AI and perception:** PyTorch, DINOv2, transformers, diffusion models, VQ-VAE, self-supervised representation learning, OpenCV, NeRF, computer vision, bioacoustic classification
- **Software and ML infrastructure:** Python, C++, DeepSpeed ZeRO-3, multi-node GPU training, Docker, experiment-control software, telemetry and metadata logging, data ingestion, dataset curation

## Engineering experience

### Center for Quantitative Genetics and Genomics, Aarhus University

**PhD Fellow** · Aarhus, Denmark · June 2025–present

- Architected a modular long-duration test platform integrating custom hardware, illumination and moisture control, continuous video capture, timestamp-aligned metadata, and experiment-management tooling.
- Implemented a repeatable image-acquisition and data-ingestion pipeline with camera control, standardized illumination, quality control, and dataset curation; produced **5,000+ curated images** across species.
- Own the full system lifecycle across hardware integration, device-control software, data schemas, computer-vision pipelines, and quantitative validation.

### Caicedo Lab, Morgridge Institute for Research

**Machine Learning Research Assistant** · Madison, Wisconsin · July 2024–May 2025

- Trained and benchmarked DINOv2, diffusion, and hierarchical VQ-VAE architectures on **1.5 million multi-channel images**, increasing gene-classification AUROC by **18%** relative to an ImageNet-pretrained baseline.
- Implemented DeepSpeed ZeRO-3 across **64 A100 GPUs**, reducing epoch latency from **6.4 hours to 1.7 hours** (**3.8× higher training throughput**) and lowering compute cost by **54%**.
- Developed a discrete latent representation pipeline using VQ-VAE token spaces for conditional generation of unseen perturbations and temporal transitions.

### Bick Lab

**Project Lead** · Madison, Wisconsin · February 2023–June 2024

- Led system architecture and validation for a bioacoustic detection device integrating contact microphones, signal preprocessing, self-supervised feature extraction, and classification; achieved **96% precision** on faint in-plant pest signals.
- Integrated low-cost LiDAR acquisition with NeRF-based 3D reconstruction, improving species-identification accuracy by **30%** in challenging capture conditions.
- Converted prototype performance into a validated technical case that contributed to **$350,000** in competitive project funding.

### UW Robotics and Graphics Lab

**Research Assistant** · Madison, Wisconsin · October 2021–December 2022

- Developed an automated extrinsic-calibration workflow for VL53L3CX and VL6180X time-of-flight sensors using ROS, Gazebo, and UR5; achieved positional accuracy of **3.18 mm and 7.29 mm** and orientation accuracy of **0.61° and 2.01°**.
- Performed end-to-end pose validation through 3D reconstruction, producing **sub-2 mm residual error** on unseen planar targets.

## Education

### Aarhus University

**PhD in Machine Learning and Agroecology** · June 2025–August 2028 (expected)

### University of Wisconsin–Madison

**MS in Computer Science**, GPA 3.8 · August 2023–May 2025<br>
**BS in Computer Science and Data Science**, GPA 3.72 · August 2021–May 2023

## Publications

- **Geometric Calibration of Single-Pixel Distance Sensors.** Carter Silverman, Dev Mehrotra, Mohit Gupta, and Michael Gleicher. *IEEE Robotics and Automation Letters* 7(3), July 2022. [DOI: 10.1109/LRA.2022.3176453](https://doi.org/10.1109/LRA.2022.3176453)
- **Eavesdropping on Herbivores: Using Contact Microphones to Quantify Plant-Insect Interactions.** Dev Mehrotra, Laurence Still, Vidit Agrawal, Kimberly Gibson, James D. Crall, and Emily N. Bick. Preprint, September 2024. [DOI: 10.1101/2024.09.23.614472](https://doi.org/10.1101/2024.09.23.614472)

## Additional technical training

- Cajal Advanced Neuroscience Training Programme—Quantitative Approaches to Behavior and Virtual Reality (2026)
- Aarhus Comprehensive Computational Entomology Summer School, ACCESS-2025 (September–October 2025)
- CaPriC PhD School on Cyber-Physical Computing Systems (October 2025)
- Morgridge Entrepreneurial Bootcamp
- NSF I-Corps Regional Program; advanced toward the national I-Corps track

## Technical leadership and mentoring

- **Huangjing Qin** (2025): computer-vision pipelines and dataset development for behavioral phenotyping
- **Alex Arovas** (2024): embedded sensing systems and experimental data acquisition
- **Rishit Malpani** (2024): OpenCV analysis and acoustic sensor integration
- **Nachiket Kerai** (2024): LiDAR sensing and NeRF workflows
- **Vidit Agrawal** (2023–2024): unsupervised learning for unlabeled acoustic data

## Cross-institutional engineering collaborations

- **Rothamsted Research, UK:** integrated pest management and ML-enabled sensor development
- **Kansas State University:** pest-monitoring and crop-protection technology
- **Missouri Soybean Extension:** soybean pest management and sustainable agriculture
- **California Extension:** precision agriculture, automation, and ML-enabled monitoring

## Recognition

- **Antlion Pitch Competition:** first place and $5,000 award
- **Wisconsin Governor’s Business Plan Contest:** semi-finalist
- **World AgriTech Featured Showcase:** $7,200 in support

## Product communication and public engagement

- Falling Walls Competition (2024)
- World AgriTech Innovation Conference (2024)
- Entomological Society of America Conference—Antlion competition pitch, winner (2024)

## In the media

- [Wisconsin Governor’s Business Plan Contest: 52 entries advance](https://www.wispolitics.com/2024/wisconsin-governors-business-plan-contest-from-30-communities-statewide-52-entries-advance-in-2024/)—WISPOLITICS, 2024
- [60+ AgTech pioneers to showcase breakthrough innovations](https://www.seedworld.com/us/2024/02/16/60-agtech-pioneers-to-showcase-breakthrough-innovations-at-world-agri-tech-in-san-francisco/)—SeedWorld, 2024
- [Insect Eavesdropper: Digital Monitoring of Crop Pests Via Vibrational Signals](https://entomologytoday.org/2024/01/17/insect-eavesdropper-digital-monitoring-crop-pests-vibrational-signals-antlion-pit-competition/)—Entomology Today, 2024

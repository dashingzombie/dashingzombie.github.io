---
permalink: /
title: "Dev Mehrotra"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div class="home-intro">
  <p class="home-eyebrow">Intelligent hardware · AI & perception · ML infrastructure</p>
  <h2 class="home-headline">I engineer intelligent systems from sensor to model.</h2>
  <p class="home-lede">I’m an ML and hardware engineer completing a PhD at Aarhus University. I build end-to-end systems that connect custom sensing hardware, computer vision, machine learning, and reliable data infrastructure—from automated imaging platforms to bioacoustic pest detection.</p>
  <div class="home-actions">
    <a class="btn btn--primary" href="/portfolio/">View engineering projects</a>
    <a class="btn btn--inverse" href="/publications/">View publications</a>
    <a class="home-text-link" href="mailto:devd@qgg.au.dk">Get in touch <span aria-hidden="true">→</span></a>
  </div>
</div>

<div class="home-capabilities" aria-label="Core capabilities">
  <div><strong>Hardware & robotics</strong><span>Custom sensing, imaging systems, LiDAR, embedded acquisition, environmental control, and robot-assisted calibration</span></div>
  <div><strong>AI & perception</strong><span>Computer vision, self-supervised learning, multimodal data, generative models, and bioacoustic classification</span></div>
  <div><strong>Software & infrastructure</strong><span>Python and C++, distributed GPU training, experiment control, metadata systems, and reproducible data pipelines</span></div>
</div>

## Selected engineering projects

<div class="project-grid">
  <article class="project-card project-card--green">
    <span class="project-kicker">Hardware · automation</span>
    <h3>Automated experimental platform</h3>
    <p>Integrated environmental control, continuous video capture, device orchestration, long-run experiment management, and timestamp-aligned metadata in a modular test platform.</p>
    <a href="/portfolio/portfolio-2/">View the system <span aria-hidden="true">→</span></a>
  </article>
  <article class="project-card project-card--blue">
    <span class="project-kicker">AI · infrastructure</span>
    <h3>Scalable visual representation learning</h3>
    <p>Benchmarked DINOv2, diffusion, and VQ-VAE architectures on 1.5 million multi-channel images; improved classification AUROC by 18% and optimized 64-GPU training.</p>
    <a href="/portfolio/portfolio-4/">Read the project <span aria-hidden="true">→</span></a>
  </article>
  <article class="project-card project-card--amber">
    <span class="project-kicker">Sensors · applied ML</span>
    <h3>Bioacoustic detection system</h3>
    <p>Integrated contact-microphone acquisition with self-supervised feature learning and classification, reaching 96% precision on faint in-plant pest signals.</p>
    <a href="/portfolio/portfolio-1/">Read the project <span aria-hidden="true">→</span></a>
  </article>
</div>

## Core engineering skills

<div class="skills-grid">
  <section>
    <h3><i class="fas fa-microchip" aria-hidden="true"></i> Hardware & robotics</h3>
    <p><strong>Build:</strong> custom experimental platforms, camera and illumination systems, environmental control, embedded acquisition, and bioacoustic devices.<br><strong>Integrate:</strong> LiDAR, time-of-flight sensors, contact microphones, UR5, ROS, and Gazebo.</p>
  </section>
  <section>
    <h3><i class="fas fa-brain" aria-hidden="true"></i> AI & perception</h3>
    <p><strong>Develop:</strong> computer-vision, bioacoustic, and representation-learning pipelines.<br><strong>Methods:</strong> PyTorch, DINOv2, transformers, diffusion models, VQ-VAE, OpenCV, NeRF, and self-supervised learning.</p>
  </section>
  <section>
    <h3><i class="fas fa-server" aria-hidden="true"></i> Software & infrastructure</h3>
    <p><strong>Engineer:</strong> Python and C++ services, experiment-control software, structured datasets, metadata logging, and reproducible pipelines.<br><strong>Scale:</strong> DeepSpeed ZeRO-3, distributed GPU training, Docker, and 64×A100 workloads.</p>
  </section>
</div>

## How I work

I work across the full engineering stack: define the measurement problem, prototype and integrate the hardware, build the acquisition software, structure the data, train the models, and validate the complete system. That end-to-end perspective helps me find failures at the interfaces between hardware, software, and ML—where many real-world systems break down.

My PhD and research roles have given me experience owning ambiguous technical problems, rapidly learning across disciplines, and turning prototypes into dependable platforms. I’m interested in bringing that experience to industry teams building robotics, intelligent devices, computer-vision products, or applied ML systems.

## Engineering results

- **Computer-vision model benchmarking:** trained and evaluated DINOv2 representations on **1.5 million multi-channel images**, increasing gene-classification AUROC by **18%** relative to an ImageNet-pretrained baseline.
- **Distributed-training optimization:** implemented DeepSpeed ZeRO-3 across **64 A100 GPUs**, reducing epoch latency from **6.4 hours to 1.7 hours**—a **3.8× throughput improvement**—while lowering compute cost by **54%**.
- **Bioacoustic classification pipeline:** integrated contact-microphone acquisition, signal preprocessing, self-supervised feature extraction, and classification to achieve **96% precision** on in-plant pest detection; the validated system supported **$350,000** in project funding.
- **Extrinsic sensor calibration:** automated calibration of VL53L3CX and VL6180X time-of-flight sensors with ROS, Gazebo, and UR5, validating sensor poses through 3D reconstruction with **sub-2 mm residual error**.
- **Automated imaging and data ingestion:** integrated camera control, standardized illumination, structured metadata, and dataset curation into a repeatable pipeline that produced **5,000+ curated images** across species.

<div class="home-contact">
  <div>
    <p class="home-eyebrow">Let’s connect</p>
    <h2>Building a product where hardware meets AI?</h2>
    <p>I’m interested in ML engineering, computer vision, robotics, and intelligent-device opportunities where end-to-end systems thinking matters.</p>
  </div>
  <a class="btn btn--primary" href="mailto:devd@qgg.au.dk">Email me</a>
</div>

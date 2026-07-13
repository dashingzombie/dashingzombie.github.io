---
title: "Bioacoustic Pest Detection System"
excerpt: "A contact-microphone acquisition and classification pipeline achieving 96% precision on faint in-plant pest signals."
collection: portfolio
---

## Challenge

Pests feeding inside plants produce signals too faint and noisy for conventional monitoring. The system needed to capture those vibrations reliably and distinguish meaningful activity from background noise.

## System

As project lead, I took the **Insect Eavesdropper** from concept through system validation. The architecture connects contact-microphone acquisition, signal preprocessing, self-supervised feature extraction, and classification in an end-to-end detection pipeline.

## Engineering contributions

- Implemented DINO, autoencoder, and transformer-based representation learning for large, sparsely labeled acoustic datasets.
- Integrated low-cost LiDAR acquisition with NeRF-based 3D reconstruction, improving species-identification accuracy by **30%** under challenging capture conditions.
- Defined repeatable acquisition, preprocessing, feature-extraction, classification, and evaluation stages for low-amplitude vibrational signals.

## Result

The classification pipeline reached **96% precision** on in-plant pest detection. The validated prototype and performance data supported **$350,000 in project funding**, a first-place pitch award, and selection for the World Agri-Tech Innovation Summit.

[Read the preprint](https://doi.org/10.1101/2024.09.23.614472)

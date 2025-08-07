---
layout: default
title: Resume
---

<h2>
  <i class="fa-solid fa-file-pdf"></i>
  Resume
</h2>

<p>
  <a href="{{ site.baseurl }}/files/CV- Yindong Hua_2025.pdf"
     target="_blank"
     class="resume-open">
    <i class="fa-solid fa-external-link-alt"></i>
    View my resume (PDF)
  </a>
</p>

## Contact Information

- **Name:** Yindong Hua
- **Phone:** 631-820-5091  
- **Email:** [yindong.hua@stonybrook.edu](mailto:yindong.hua@stonybrook.edu)  
- **Address:** 8 Hirsch Ave, Coram, NY, 11727

## Education

- **Ph.D. in Computer Engineering**  
  *Stony Brook University, 01/2020 - 12/2025*

- **Master of Electrical Engineering**  
  *Peking University, 09/2013 - 07/2016*

- **Bachelor of Electrical Engineering**  
  *Henan University, 09/2009 - 07/2013*

## Research Experience

### Research Assistant at Stony Brook University

**Project: Motion-Based Computer Vision for Consciousness Recovery (10/2024-present).**
- Developed a convolutional VAE model using Pytorch to encode high-dimensional facial motion trajectories into robust, low-dimensional (128-dim) latent embeddings, achieving an average reconstruction MSE of 0.012.
- Built and optimized a Transformer encoder to predict future latent vectors from historical embeddings, effectively capturing temporal dependencies in patient motion and attaining a shorter ahead forecasting (<= 10-step) for less coma patients.
- Validated the hypothesis linking motion predictability to consciousness recovery by stratifying results using Glasgow Coma Scale (GCS) and movement labels, generated detailed visualizations of prediction-error trajectories.

**Project: Contrastive Learning with LLM for Consciousness Level Classification (09/2023-09/2024).**
- Created a custom EEG Dataset object with strategic daily segment selection per subject to maintain balanced class distribution, improving model generalizability.
- Built a dual-encoder architecture (CNN-based patch embedding + GPT-2 LLM backbone) for robust EEG feature extraction.
- Implemented advanced contrastive learning to learn shared (common across subjects), private (subject-specific), and orthogonal (disentangled) EEG representations using NT-Xent loss and orthogonality constraints.
- Fine-tuned embeddings on Glasgow Coma Scale (GCS) prediction, achieving strong classification performance (Accuracy:
76%, AUROC: 0.85, F1-score: 0.74).

**Project: Scalable Home-Based Health Monitoring Infrastructure (10/2022-08/2023).**
- Engineered a scalable, manageable, and fault-tolerant IoT-based distributed health monitoring system using Python and Node.js, utilizing microservices architecture and Docker containerization for modular deployment and CI/CD practices via
AWS Greengrass.
- Created a data-agnostic pipeline using publish-subscribe mechanisms, reducing configuration efforts by 25x.
- Implemented automated monitoring and recovery with logging, dashboards, caching strategies, and reboot protocols.
- Leveraged InfluxDB and MySQL for high-availability time-series and relational data storage, ensuring data integrity.
- Validated system performance in a simulated smart home environment with 26 sensor nodes, achieving robust 24/7 operation with less than 1% data loss.

**Project: Radar-based Non-contact Vital Signs Monitoring (01/2021 - 10/2022).**  
- Led development of an advanced radar signal processing system in Python for non-contact vital signs monitoring.
- Proposed a dynamic range-bin selection algorithm that improved the Periodic-to-Noise Ratio by 2 dB.
- Applied filtering techniques to reduce respiration error to 1.2 beats per minute.

### Research Scholar at Texas A&M University

**Project: Deep Learning for Monocular Depth Estimation (08/2018 - 06/2019)**  
- Developed a dilated fully convolutional neural network (CNN) using Python and PyTorch for monocular depth estimation.
- Implemented dilated convolutions to expand the receptive field, achieving a 7x reduction in parameters compared to VGG-16.

## Publications

- **Proteus: Towards a Manageability-focused Home-based Health Monitoring Infrastructure.**  
  Proceedings of the 14th ACM International Conference on Bioinformatics, Computational Biology and Health Informatics, 2023.
- **A Study of Practical Radar-based Nighttime Respiration Monitoring at Home.**  
  IEEE Radar Conference (RadarConf23), 2023.
- **Dilated Fully Convolutional Neural Network for Depth Estimation from a Single Image.**  
  2019 International Conference on Computational Science and Computational Intelligence (CSCI), IEEE, 2019.

## Technical Skills

- **Programming Languages:** Python, Java, Node.JS, C, Matlab  
- **Tools & Platforms:** GitHub, Docker, AWS (EC2, Greengrass, S3), Linux/Unix  
- **Databases:** InfluxDB, MySQL, Redis


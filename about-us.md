---
layout: post
title: About Us
permalink: /about/
description: 'Who we are, what we do'
image: assets/images/logo.png
nav-menu: true
---

# About MIMIC Lab

The Multimodal Interactive Machine Intelligence Creation Laboratory is dedicated to advancing human-interactive, multimodal AI. 

Our focus is on creating AI that can understand, communicate with, and empathize with humans.

# Taehoon Kim

## Education
2018 - 2021 Ph.D (M.S integrated) in Computer Science, Sogang University 

2012 - 2018 B.S in Computer Science & Communications, Sogang University

## Career
Aug 2024 - Current Assistant Professor, Graduate School of Metaverse, Sogang University

Mar 2021 - Aug 2024 Research Scientist, Vision Lab, LG AI Research

Feb 2020 - Jan 2021 Research Intern, Clova AI, Naver Corp.

Jan 2017 - Dec 2017 Machine Learning Engineer, Nosith Inc.

## Field of Interest
• General machine learning, computer-vision, and large scale model training.

• Specialized in large multimodal model (LMM), vision-language, quantization, and network architecture design.

• Application of machine learning algorithms on various multimodal and computer vision tasks.

## Projects

### Physics-Informed AI for Mega-Scale Content Simulation and Direction

• Research supported by the [Korea Creative Content Agency (KOCCA)](http://www.kocca.or.kr) under the 2026 Culture, Sports and Tourism R&D Program.  

• Developing a Physics-Informed AI (PI-AI) platform that integrates real-time physics simulation, digital twins, and intelligent production tools for K-POP concerts, festivals, exhibitions, and other mega-scale cultural content.  

• Building a physics-aware content asset database containing more than 500 stage structures, lighting systems, cameras, LED displays, and moving devices, with physical properties such as mass, center of gravity, load capacity, friction, collision range, and motion limits.  

• Developing a hybrid physics architecture in which PI-AI models complement conventional physics engines by learning and correcting residual errors between simulated behavior and real-world measurements.  

• Developing real-time safety validation models that detect excessive loads, structural instability, collisions, and equipment operating-limit violations, targeting safety parameter inference within 100 ms.  

• Designing AI-assisted production tools that automatically recommend camera positions, lighting configurations, equipment layouts, and directing sequences while considering visibility, illumination uniformity, physical constraints, and operational safety.  

• Implementing a Hybrid Neural Rendering Digital Twin that combines 3D Gaussian Splatting for photorealistic venue reconstruction with mesh-based dynamic simulation and AI-based relighting for physically consistent integration of virtual and real environments.  

• Enabling bidirectional synchronization between Unity-based virtual environments and real stage equipment through protocols such as sACN, Art-Net, FreeD, Modbus, MQTT, OSC, and SMPTE timecode, targeting real–virtual content synchronization delays below 10 seconds.  

• Developing automatic calibration methods to align virtual and physical stages, targeting an SSIM-based physical alignment accuracy of 0.75 and a spatial alignment error below 0.8 degrees.  

• Validating the platform through real-world K-POP concerts and large-scale event productions to reduce production risks, improve pre-visualization workflows, and support simultaneous offline, online, and metaverse-based performances.

### Reliable Egocentric Multimodal AI Agent (NRF Early Career Research)
• Research supported by [National Research Foundation (NRF)](https://www.nrf.re.kr/) Early Career Research Program (우수신진연구).  

• Developing a hallucination-free on-device egocentric multimodal AI agent with self-correction capabilities, designed to operate in real-world human environments.   

• Proposing an Actor-Validator architecture with RLAIF-based alignment, where a lightweight actor generates responses and a high-capacity validator evaluates factual consistency, logical coherence, and social appropriateness.  

• Designing a Social-Context Hallucination Benchmark to quantitatively measure and reduce hallucinations in egocentric multimodal settings, targeting hallucination rates below 10%. 

• Developing multimodal data augmentation pipelines using large multimodal models to improve robustness in rare and socially complex scenarios. 

• Implementing Dynamic Precision Quantization (DPQ) and Quantization-Aware Training (QAT) to enable real-time on-device inference under strict resource constraints (≤4GB memory, ≤100ms latency).  

• Integrating privacy-preserving mechanisms based on latent-space anonymization to ensure safe handling of egocentric visual and audio data. 

• Targeting deployment on edge devices such as Jetson Orin and NPU platforms, enabling fully on-device, privacy-preserving, and low-latency AI agents for AR/XR and wearable applications.  

### Reliable Generative AI via Validator LLM
• Academic research supported by NVIDIA Academic Grant Program.

• Developing a Validator LLM framework to evaluate and enforce logical consistency in generative AI outputs, addressing hallucination and reasoning errors in large language models.

• Designed a dual-model architecture where an actor LLM generates responses and a validator LLM assesses reasoning validity, enabling iterative refinement through reinforcement learning from AI feedback (RLAIF).

• Exploring multi-pass reasoning and cross-model verification to improve robustness and trustworthiness of generated explanations.

• Implementing the system using NVIDIA AI stack including NeMo Framework and TensorRT-LLM for scalable and production-ready deployment.

### Egocentric Multimodal AI Agent
• Academic Partnership with Project Aria, Meta Reality Lab. (On-going)

• Developing an Egocentric Multimodal AI Agent leveraging real-time visual inputs from Aria Glass, integrating camera streams, Visual SLAM, and eye-tracking data to enable personalized and context-aware interactions.

• Designing end-to-end multimodal AI architecture optimized for egocentric perception, combining Large Multimodal Models (LMM) with Speech-to-Text (STT) and Text-to-Speech (TTS) for immersive, real-world applications.

### Large Multimodal Model (LMM)
• Lead of Image-to-Text LMM (EXAONE Atelier Image-to-text) Project.

• Developed Bidirectional Image-Text Transformer architecture for efficient large-scale vision-language model training.

• Optimized model inference and corresponding backend architecture for commercialization.

• Designed end-to-end backend architecture for general-purpose multimodal agent
(EXAONE Atelier Multimodal) by integrating large multimodal model (LMM) and large language model (LMM) with instruction prompt engineering.

### Quantization and Network Architecture Search
• Cooperative project with CLOVA AI, Naver Corp.

• Developed a straightforward optimization methods StatAssist & GradBoost which enables the scratch quantization-aware-training in various computer vision tasks : classification, object detection, semantic segmentation, and style transfer.

• Experiments on various tasks showed comparable or often better performance than their floating-point baselines.

### Privacy Preserving Image Anonymization
• Project supported by the Institute for Information and Communications Technology Promotion (IITP) Grant funded by the Korea Government (MSIT) (A Development of Deidentification Technique Based on Differential Privacy)

• Developed a latent-space-level image anonymization framework (PPAPNet & PPSGAN) based on Generative Adversarial Networks (GANs) and Differential Privacy to potentially protect images from Model Inversion Attacks.

• Experiments on various datasets showed that PPAPNet & PPSGAN can effectively convert a sensitive image into a high-quality and attack-immune synthetic image while preserving its utility as training data.

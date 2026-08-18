<p align="center">
  <img src="profile-banner.png" width="100%" alt="Generative AI, computer vision, and robot learning banner" />
</p>

<h1 align="center">Tauhid Khan</h1>

<p align="center">
  <strong>AI Research Engineer | Generative AI | Computer Vision | Robot Learning</strong>
</p>

<p align="center">
  I build research-driven machine learning systems, from model design and large-scale training to efficient production deployment.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/tauhid-khan-24bb45177/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://scholar.google.com/citations?user=_AGKM0cAAAAJ&hl=en">
    <img src="https://img.shields.io/badge/Google_Scholar-Research-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white" alt="Google Scholar" />
  </a>
  <a href="https://openreview.net/forum?id=HR70n1Pv5A">
    <img src="https://img.shields.io/badge/OpenReview-IsoFM-B31B1B?style=for-the-badge" alt="IsoFM on OpenReview" />
  </a>
  <a href="mailto:mail2tauhidkhan@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

---

## About

I am an AI Research Engineer with 4+ years of experience across generative AI, computer vision, multimodal learning, and efficient inference. At Fynd, I develop production image and video systems involving Flow Matching, diffusion models, super-resolution, distributed PyTorch training, model distillation, and TensorRT optimization.

Previously, at Wobot.ai, I built large-scale video analytics systems for detection, multi-object tracking, and cross-camera association. Alongside my industry work, I pursue research in generative modeling and robot learning through publications and open-source projects.

My current interests sit at the intersection of generative vision and embodied intelligence: learning representations, trajectories, and policies that are accurate, efficient, and deployable.

## Research And Engineering Focus

| Generative Vision | Computer Vision | Robot Learning |
| --- | --- | --- |
| Flow Matching and diffusion models | Detection, segmentation, and tracking | Vision-Language-Action models |
| Image and video generation | Image and video restoration | Visuomotor policy learning |
| Super-resolution and one-step distillation | Multimodal and representation learning | Imitation and reinforcement learning |
| Controllable generation and PEFT | Production GPU inference | Simulation, evaluation, and Sim2Real |

## Selected Impact

| Area | Result |
| --- | --- |
| Generative super-resolution | Built a 4x Flow Matching system and distilled it into a single-step generator |
| Efficient inference | Reduced super-resolution latency by approximately 40-45% with TensorRT |
| High-resolution processing | Processed 2500x2500 inputs in approximately 4-5 seconds on one NVIDIA L4 GPU |
| Production media AI | Built image and video services supporting approximately 20K daily active users |
| Video restoration | Improved end-to-end latency by up to 56% and reduced compute cost by up to 52% |
| Large-scale video analytics | Deployed tracking pipelines across 1,000+ cameras at 250+ locations |
| Robot learning | Reached a 95.5% StackCube-v1 success rate with a Flow Matching Transformer and ViT policy |

## Publication

### Isokinetic Flow Matching for Pathwise Straightening of Generative Flows

Accepted at the **ICML 2026 Workshop on Structured Probabilistic Inference and Generative Modeling (SPIGM)**.

[Read the paper on OpenReview](https://openreview.net/forum?id=HR70n1Pv5A)

The work studies a geometry-aware Flow Matching formulation for straighter generative transport paths and more efficient generation.

## Experience

| Period | Role | Work |
| --- | --- | --- |
| Sep 2023 - Present | **ML Research Engineer, Fynd** | Flow Matching super-resolution, single-step distillation, SDXL and FLUX training, video segmentation and inpainting, controllable generation, distributed PyTorch, and TensorRT deployment |
| Feb 2022 - Sep 2023 | **Computer Vision Engineer, Wobot.ai** | Production detection and tracking, multi-camera analytics, CPU and GPU pipeline optimization, Docker, and NVIDIA Triton deployment |

## Featured Projects

### [mini-pi0](https://github.com/Thehunk1206/mini-pi0)

An open-source multimodal robot-learning framework inspired by pi0-style manipulation policies. It combines ManiSkill, MuJoCo, wrist-camera observations, and custom visuomotor Flow Matching policies for action trajectory prediction and control.

- 95.5% success rate on ManiSkill StackCube-v1
- Flow Matching Transformer and ViT policy
- VLA, imitation-learning, and reinforcement-learning experiments
- [View updated task benchmarks](https://github.com/Thehunk1206/mini-pi0/blob/main/docs/TASK_BENCHMARK.md)

### [Flow-Based Models](https://github.com/Thehunk1206/flow-based-models)

Implementations and experiments for Conditional Flow Matching across image and video generation, including optimal-transport paths, ODE-based sampling, and diffusion-related formulations.

### [VideoGen MeanFlow](https://github.com/Thehunk1206/videogen-mean-flow)

A complete training and inference pipeline for video generation using MeanFlow with a Diffusion Transformer architecture.

### [Zero-DCE](https://github.com/Thehunk1206/Zero-DCE)

A TensorFlow implementation of zero-reference low-light image enhancement. The repository has earned **49+ stars** and **8+ forks**.

### [PraNet Polyp Segmentation](https://github.com/Thehunk1206/PRANet-Polyps-Segmentation)

A TensorFlow implementation of Parallel Reverse Attention Network for medical-image segmentation, with **24+ stars**.

### [TinyML Audio Classification](https://github.com/Thehunk1206/Arduino-Surrounding-Sound-Classifier)

An INT8-quantized deep audio-classification pipeline for Arduino Nano BLE Sense, designed to operate within a memory budget below 20 KB.

## Current Build

I am building an **SO-ARM101 from individual components rather than using a pre-assembled system**. The goal is to connect simulation-based policy development with physical data collection, evaluation, and learned-policy deployment. Hardware integration and real-world policy testing are currently in progress.

## Technical Skills

### Core Machine Learning

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

`Representation Learning` `Multimodal Learning` `Distributed Training` `DDP` `FSDP`

### Generative AI

`Diffusion Models` `Flow Matching` `SDXL` `FLUX` `Super-Resolution` `Flow Distillation` `One-Step Generation` `Image Generation` `Video Generation` `IP-Adapters` `Textual Inversion` `LoRA` `PEFT`

### Computer Vision

`Object Detection` `Multi-Object Tracking` `Image Segmentation` `Video Segmentation` `Image Restoration` `Video Restoration` `Vision-Language Models` `Controllable Generation`

### Robotics And Robot Learning

![MuJoCo](https://img.shields.io/badge/MuJoCo-Robot_Learning-222222?style=flat-square)
![NVIDIA Isaac Sim](https://img.shields.io/badge/Isaac_Sim-76B900?style=flat-square&logo=nvidia&logoColor=white)
![LeRobot](https://img.shields.io/badge/LeRobot-FFD21E?style=flat-square)

`Vision-Language-Action Models` `Robotic Manipulation` `Visuomotor Policies` `Imitation Learning` `Reinforcement Learning` `Flow Matching Policies` `ManiSkill` `Robosuite` `Sim2Real`

### Deployment And Infrastructure

![NVIDIA](https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Weights & Biases](https://img.shields.io/badge/Weights_&_Biases-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black)

`NVIDIA Triton Inference Server` `MLflow` `GPU Optimization` `Model Serving` `Data Curation` `Experiment Tracking`

## Education

**Bachelor of Science in Computer Science**, University of Mumbai, 2022  
CGPA: **9.21/10**

## Connect

I am interested in research and engineering conversations around generative vision, efficient deep learning, multimodal intelligence, and learning-based robotics.

- Email: [mail2tauhidkhan@gmail.com](mailto:mail2tauhidkhan@gmail.com)
- LinkedIn: [tauhid-khan-24bb45177](https://www.linkedin.com/in/tauhid-khan-24bb45177/)
- Google Scholar: [Tauhid Khan](https://scholar.google.com/citations?user=_AGKM0cAAAAJ&hl=en)
- OpenReview: [Isokinetic Flow Matching](https://openreview.net/forum?id=HR70n1Pv5A)

<p align="center">
  <sub>Research depth. Engineering rigor. Systems that run outside the notebook.</sub>
</p>

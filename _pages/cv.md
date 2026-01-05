---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Shanghai Jiao Tong University (SJTU), Shanghai, China  
  Junior in Electrical & Computer Engineering, Sept. 2023 - Present  
  GPA: 3.67/4.0; Rank: 52/262  
  Relevant Coursework: Algorithms (ECE4770J), Algorithms for Big Data (Res1102), Numerical Analysis (MATH4710J), Computer Architecture, Probability and Statistics, Linear Algebra  
  Awards: Gold Medal University Physics Competition (Top 5%); Feng Tongsheng Scholarship (University-level)

Research and Technical Projects
======
* Neural Network-based Numerical Integration (Course Project, MATH471: Numerical Analysis), FA2025  
  * Neural Approximation & Data Pipeline: Built neural-network-based function approximators for definite integrals using PyTorch, including synthetic data generation, model definition, and batched training with DataLoader.
  * Training, Evaluation & Stability Analysis: Implemented end-to-end training and evaluation workflows (forward/backward propagation, loss monitoring, MAE/MSE evaluation), and analyzed numerical stability and generalization under different function smoothness and sampling resolutions.

* Machine Learning and Large-Scale Algorithm Optimization (Course Project, Res1102: Algorithms for Big Data), FA2025  
  * Classical-to-RNN Stack: Implemented perceptron, regression MLP, MNIST classifier, and language-ID RNNs with PyTorch Modules, DataLoader pipelines, and custom gradient-descent loops, validating each stage via numpy/matplotlib instrumentation and disciplined loss tracking.
  * Transformer & GPT Tooling: Built a masked-attention transformer with LayerNorm, residual connections, and autoregressive sampling to power a character-level GPT, leveraging cross-entropy training, torch.nn.functional utilities, and reproducible generation scripts for trustworthy evaluation.

* Algorithms & AI Foundations Self-Study Module (Self-directed & Course Project, ECE477: Intro to Algorithm), 2025.6-2025.12  
  * Advanced Algorithmic Thinking for AI: Systematically studied advanced algorithms (graph algorithms, search, optimization, matching, and randomized algorithm), with emphasis on their role in AI problem solving such as search, planning, and decision-making.
  * Collaborative Algorithm Wiki Project: Co-authored a structured algorithm wiki using Git and LaTeX in a team setting, focusing on clear exposition of algorithmic ideas, correctness, and complexity, following reproducible and standardized documentation practices.

Work experience
======
* Teaching Assistant - Intro to Circuits (ECE2150J), Shanghai Jiao Tong University, Shanghai, China (SU2025)  
  * Provided technical guidance on circuit analysis and simulations, assisting students in debugging and experimental design.
  * Demonstrated strong responsibility, communication skills, and long-term commitment in an academic setting.
  
Skills
======
* Programming: Python (PyTorch), C/C++, OCaml, MATLAB, LaTeX, Verilog.
* ML Training & Optimization: End-to-end PyTorch pipelines (Dataset/DataLoader, train/val loops, checkpointing, reproducibility); regression/classification; Adam/SGD, LR scheduling, regularization, loss engineering (MSE/Huber, multi-task losses), hyperparameter tuning.
* Simulation & Experimentation: Learning-based experiments in simulated environments, including CARLA and Habitat-Lab; evaluation with MAE/RMSE/F1 and error breakdowns.
* Environment & Writing: Proficient with Ubuntu-based AI development (conda, CUDA-ready PyTorch, Git, Docker, SSH); experienced in formal academic writing and collaborative workflows using LaTeX and Git.

Leadership and Awards
======
* Gold Medal, University Physics Competition (FA2024, SJTU)  
  * Aerodynamic Modeling and Analysis: Led the modeling and analysis of a three-dimensional aerodynamic problem, translating physical assumptions into simulation-ready formulations and interpreting quantitative results from the simulated flow field.
  * 3D Physical Simulation with Ansys: Proposed and implemented a 3D simulation workflow using Ansys to study airflow behavior and system response, increasing the final report's confidence factor by 30%.

* Feng Tongsheng Scholarship (Merit-based, University-level), FA2025

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

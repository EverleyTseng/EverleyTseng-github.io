---
title: Research & Technical Background
---

<nav style="margin: 0.5rem 0 1rem 0;">
  <a href="{{ '/' | relative_url }}">Home</a>
  &nbsp;•&nbsp;
  <a href="{{ '/research' | relative_url }}">Research</a>
  &nbsp;•&nbsp;
  <a href="{{ '/CV_Everley_Tseng_Sep25.pdf' | relative_url }}">CV</a>
</nav>

# Research & Technical Background

## Research Overview

My Ph.D. research focuses on building and evaluating AI systems—particularly computer vision and vision–language models (VLMs)—that interact with real users under practical constraints such as privacy, ambiguity, and accessibility. Rather than optimizing models in isolation, my work emphasizes **dataset design, benchmarking, and evaluation infrastructure** as first-class research contributions.  

A central goal of my research is to expose gaps between current model performance and real-world user needs, especially for people who are blind or have low vision, and to translate these insights into reliable, deployable systems.

---

## Research Themes

- **Vision–language model evaluation and benchmarking**  
  Systematic analysis of VLM behavior under ambiguity, incomplete visual grounding, and real-user image distributions.

- **Dataset design for real-world and privacy-sensitive scenarios**  
  Creating datasets that surface underexplored challenges such as private content, user intent ambiguity, and accessibility-driven data collection.

- **Few-shot learning and segmentation under ambiguity**  
  Studying how models generalize with limited supervision and how ambiguity affects localization and segmentation tasks.

- **Human-centered and accessibility-aware AI**  
  Designing evaluation protocols and benchmarks grounded in the needs and practices of blind and low-vision users.

- **Evaluation infrastructure for large-scale model comparison**  
  Building reusable, scalable systems for benchmarking models across datasets, tasks, and research communities.

---

## Selected Publications & Projects

### **BIV-Priv-Seg: Locating Private Content in Images Taken by People with Visual Impairments**  
*WACV 2025 (Oral Presentation)*  

Introduced a benchmark and evaluation protocol for detecting privacy-sensitive content in images captured by blind and low-vision users. The dataset and benchmark highlight systematic failures of existing vision models in privacy-critical scenarios and provide standardized metrics for evaluating privacy-aware perception systems.

---

### **Accounting for Visual Questions with Focus Ambiguity**  
*ICCV 2025*  

Investigated how focus ambiguity arises in visual question answering and how current evaluation practices fail to capture this phenomenon. Proposed formal definitions and evaluation strategies for ambiguity-aware VQA, revealing limitations in both model reasoning and benchmark design.

---

### **VizWiz-FewShot: Locating Objects in Images Taken by People with Visual Impairments**  
*ECCV 2022*  

Developed a few-shot object localization dataset based on real images taken by blind users. The project includes annual public challenges and leaderboards, enabling systematic comparison of few-shot and zero-shot models in accessibility-driven vision tasks.

*(A full publication list is available upon request.)*

---

## Applied Systems & Evaluation Infrastructure

- Designed and maintained **evaluation servers, submission pipelines, and public leaderboards** for annual dataset challenges hosted at CVPR and related venues.
- Built **participant-facing workflows, documentation, and tooling** used by an international research community spanning academia and industry.
- Developed **reusable operational templates and benchmarking pipelines** that have been adopted and extended by other academic workshops and dataset challenges.

---



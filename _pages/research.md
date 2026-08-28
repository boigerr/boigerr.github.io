---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research lies at the intersection of **applied mathematics, machine learning, scientific computing, and environmental and materials sciences**.

I develop computational and data-driven methods for complex scientific problems, with a particular focus on **scientific machine learning, explainable AI, uncertainty quantification, surrogate modelling, inverse problems, and optimization**.

A central question underlying my research is:

> **How can we combine data, mathematical models, physical understanding, and machine learning to obtain reliable knowledge from complex scientific systems?**

My current research program is organized around three closely connected themes.

---

## 1. Explainable and Uncertainty-Aware Machine Learning for Geoscience

Modern geological investigations generate large and heterogeneous datasets, including drill-core images, borehole logs, geophysical measurements, and laboratory analyses.

I develop **machine-learning and computer-vision methods** to extract quantitative geological information from these data.

### Characterization of Rocks with Explainable and Uncertainty-Aware Machine Learning

This research is at the center of my SNSF-funded project:

**Characterization of Rocks with Explainable and Uncertainty-Aware Machine Learning**

The goal is to develop machine-learning methods for geological characterization that go beyond predictive accuracy.

In scientific applications, a prediction alone is often not sufficient. We also need to understand:

- **Why does the model make this prediction?**
- **How certain is the prediction?**
- **Which features in the data are scientifically relevant?**
- **How well does the model generalize to new geological material or measurement conditions?**

The project therefore combines **computer vision, explainable artificial intelligence, uncertainty quantification, and geological domain knowledge**.

[View the project on the SNSF Data Portal →](https://data.snf.ch/grants/grant/10006952)

### From drill-core images to geological information

One starting point for this research is our work on extracting geological information directly from drill-core images.

Deep drilling campaigns produce large quantities of core photographs together with borehole logs and laboratory measurements. Machine learning provides an opportunity to combine these heterogeneous sources of information and obtain spatially resolved predictions of geological and mineralogical properties.

Our work has demonstrated the use of transfer learning and computer vision for predicting geological properties directly from drill-core images.

[Read the PSI Research Highlight: Artificial intelligence explores the subsurface →](https://www.psi.ch/de/news/psi-stories/kuenstliche-intelligenz-erkundet-das-erdreich)

**Methods:** Computer Vision · Transfer Learning · Explainable AI · Uncertainty Quantification · Multimodal Data

---

## 2. Machine-Learning-Assisted Reactive Transport and Geochemistry

Reactive transport models describe the interaction between **transport processes and chemical reactions** in complex geological materials.

These models are essential for understanding the long-term evolution of subsurface systems and are particularly important for assessing processes relevant to **deep geological repositories for radioactive waste**.

However, coupled geochemical and transport simulations can be computationally expensive.

My research investigates how **machine learning and surrogate modelling can accelerate these simulations**.

A typical approach is to replace computationally demanding components of a physics-based simulation with a trained surrogate model while retaining the physical transport model.

This can make previously computationally prohibitive applications possible, including:

- uncertainty quantification
- sensitivity analysis
- parameter estimation
- optimization
- large parameter studies
- long-term predictions

An important aspect of my research is determining where machine learning can safely accelerate physics-based models and where the underlying physical or chemical model must remain explicitly represented.

### Towards trustworthy scientific machine learning

For me, acceleration alone is not sufficient.

Scientific machine-learning models should also provide information about **their reliability and limitations**, particularly when they are used for long-term predictions or safety-relevant applications.

I am therefore interested in combining surrogate modelling with **uncertainty quantification, physical constraints, interpretability, and rigorous validation**.

**Methods:** Surrogate Modelling · Scientific Machine Learning · Reactive Transport · Geochemical Modelling · Uncertainty Quantification · Optimization

---

## 3. Machine Learning and Optimization for Sustainable Materials

The same methodological ideas can be applied beyond geoscience.

In an interdisciplinary project at PSI, we investigated how **machine learning and mathematical optimization can accelerate the development of lower-carbon cement formulations**.

Cement production contributes substantially to global CO₂ emissions. Developing alternative cement formulations therefore involves a multi-objective problem: reducing environmental impact while retaining required material properties.

We developed a machine-learning surrogate model that predicts relevant mechanical properties from cement composition. Coupling this model with mathematical optimization enables rapid exploration of possible formulations and identification of promising candidates balancing **CO₂ emissions and material performance**.

[Read the PSI Research Highlight: Using AI to develop greener cement →](https://www.psi.ch/de/news/medienmitteilungen/mit-ki-zu-grunem-zement)

This project illustrates one of the broader goals of my research: using machine learning not merely for prediction, but as a component of **scientific discovery and optimization workflows**.

**Methods:** Neural Networks · Surrogate Modelling · Multi-Objective Optimization · Materials Informatics

---

# Methodological Foundations

Although my current applications span geoscience, radioactive waste management, and materials research, they share common mathematical and computational foundations.

## Inverse Problems

My scientific background is in **inverse problems**.

During my PhD in Technical Mathematics, I developed methods for parameter identification and uncertainty quantification in time-dependent models governed by partial differential equations.

In a forward problem, model parameters are known and we calculate the expected observations.

In an inverse problem, we instead start from observations and attempt to infer the unknown parameters or properties that produced them.

This perspective continues to influence much of my work today. Many modern machine-learning problems in science can also be viewed as inverse problems: we observe complex data and want to infer the underlying physical properties or processes.

---

## Surrogate Modelling

High-fidelity simulations can require substantial computational resources.

A **surrogate model** learns the relationship between simulation inputs and outputs and can subsequently approximate the original simulation at much lower computational cost.

I have applied this concept across several scientific domains, including:

- particle accelerator optimization
- aerosol property retrieval
- spent nuclear fuel characterization
- geochemical and reactive transport modelling
- cement optimization

The scientific challenge is not simply to train a fast neural network, but to determine whether the surrogate remains **accurate, robust, physically meaningful, and reliable in the region in which it is used**.

---

## Uncertainty Quantification

Scientific predictions are incomplete without an understanding of their uncertainty.

Uncertainty may arise from measurements, model parameters, incomplete physical knowledge, limited training data, or the machine-learning model itself.

**Uncertainty quantification** has been part of my research since my work on inverse problems and is increasingly central to my current work on trustworthy machine learning.

My goal is to develop models that can communicate not only **what they predict**, but also **how much confidence we should place in that prediction**.

---

# A Data Science Journey Across Scientific Domains

My research path has taken me through several scientific and engineering domains.

I started in **numerical mathematics and inverse problems**, before moving into applied data science and machine learning for industrial research. My subsequent work at PSI has included particle accelerators, aerosol physics, radioactive waste management, geoscience, and sustainable materials.

Some examples include:

### Particle accelerators

Machine-learning surrogate and inverse models for finding accelerator settings that produce desired beam properties.

### Aerosol physics

Inverse and machine-learning methods for retrieving aerosol properties from multi-angle light-scattering measurements.

### Spent nuclear fuel

Machine-learning surrogate models for accelerating uncertainty quantification of spent nuclear fuel characteristics.

### Geoscience

Computer vision and machine learning for extracting mineralogical and geological information from drill-core images and deep-drilling datasets.

### Reactive transport

Machine-learning-assisted geochemical calculations for accelerating coupled reactive transport simulations.

### Sustainable materials

Machine-learning surrogate models combined with mathematical optimization for discovering lower-carbon cement formulations.

---

## From Inverse Problems to Machine Learning

In 2026, I presented this scientific journey in an invited talk at **Women in Data Science Worldwide, Villach**:

**From Inverse Problems to Machine Learning: A data science journey across scientific domains**

The central message of the talk also summarizes my approach to scientific data science:

> Data science across scientific domains is not only about applying models. It is about connecting imperfect data, domain understanding, careful interpretation, and a robust data workflow to create reliable knowledge.

---

# Research Philosophy

Across these different applications, I follow a common workflow:

1. **Start with the scientific question.**  
   What do we want to understand, predict, optimize, or control?

2. **Understand the available data.**  
   Measurements, images, sensor signals, laboratory experiments, simulations, and literature data all contain different information and uncertainties.

3. **Choose the appropriate model.**  
   This may be a physical model, statistical method, machine-learning model, inverse method, or a combination of them.

4. **Validate and interpret.**  
   Predictions need to be compared with experiments and observations, uncertainties quantified, and results interpreted together with domain experts.

5. **Create scientific impact.**  
   The objective is not simply a high-performing model, but improved process understanding, faster simulations, optimized materials, or more reliable scientific predictions.

---

# Selected Projects

### SNSF — Characterization of Rocks with Explainable and Uncertainty-Aware Machine Learning

**Principal Investigator**

Explainable and uncertainty-aware machine learning for quantitative geological characterization.

[Project information →](https://data.snf.ch/grants/grant/10006952)

---

### PSI Career Return Program — Inverse Models for Particle Accelerators

**Principal Investigator · 2020–2022**

Development of inverse and machine-learning models for complex particle accelerator systems.

The PSI Career Return Program supported my return to academic research and marked the beginning of my research activities at PSI.

[About the PSI Career Return Program →](https://www.psi.ch/en/news/psi-stories/ruckkehr-in-die-berufstatigkeit-am-paul-scherrer-institut)

---

## Collaboration

My research is inherently interdisciplinary. I collaborate with researchers in **geoscience, geochemistry, radioactive waste management, materials science, physics, engineering, and applied mathematics**.

I am particularly interested in research questions where mathematical and computational methods can be developed in close interaction with **experimental data and domain expertise**.

For publications related to these research areas, see my [Publications](/publications/) page.

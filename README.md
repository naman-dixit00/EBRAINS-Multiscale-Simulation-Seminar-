# EBRAINS Multiscale Simulation: From the Neuron to the Patient

## Overview

This document provides a comprehensive overview of the EBRAINS Multiscale Simulation webinar conducted on February 5. The session featured Prof. Egidio Ugo D’Angelo (University of Pavia) and **Viktor Jirsa** (Chief Science Officer of EBRAINS), focusing on the integration of biological data and computational models across multiple scales—from cellular mechanisms to whole-brain clinical applications.

---

## 1. Multiscale Brain Organization

The core philosophy of the presentation is based on the necessity of "synthesis" in neuroscience. Understanding the brain requires bridging the gap between different levels of complexity.

* **The Challenge**: Most neuroscientists focus on narrow scales, but true synthesis requires looking across "four orders of magnitude" above and below a central focus.
* **The Goal**: To avoid viewing the brain as "dismembered parts" and instead create a unified understanding of its dynamic range.



## 2. Theoretical and Computational Frameworks

The webinar highlighted the transition from experimental data to predictive modeling through specific mathematical problems:
* **Direct vs. Inverse Problems**:
* **Direct Problem**: Using model parameters () to predict observed data ().
* **Inverse Problem**: Using observed data () to infer underlying model parameters ().

* **Theory Support**: Computational models are used to validate historical theories, such as **Marr’s Motor Learning Theory**, by predicting spatial pattern separation and adaptive filtering in the granular layer of the cerebellum.

* **Model Prediction and Validation**: The presentation demonstrated how models can predict synaptic plasticity (e.g., STDP in cerebellar Golgi cells), which is subsequently verified through experimental demonstrations (e.g., Pali et al., 2025).



## 3. Network Simplification & Mean Field Models

To scale from individual neurons to full-brain simulations, the researchers utilize network simplification techniques.

* **From Spiking to Mean Field**:
* **Spiking Neural Networks (SNN)**: Detailed, bottom-up simulations of point-neuron populations.
* **Mean Field Approximation**: Simplifying complex population activity into mean field models to simulate large-scale brain dynamics.
* **Hybrid Brain Digital Twin**: Integrating bottom-up biological properties into mean field models to create a functional digital twin.



## 4. The Virtual Brain Twin (VBT) Workflow
A major highlight of the webinar was the **Virtual Brain Twin**, a unified platform designed for patient care and clinical research.

### Data Integration & Reconstruction

* **Patient Entry Data**: The workflow begins with collecting patient-specific data, including **MRI**, **SEEG**, and **EEG**.
* **Personalization**: Imaging data is used to reconstruct a patient’s unique **Connectome** and brain atlas (VEP atlas).

### Clinical Applications

* **Epilepsy Use Case**: The VBT is used to simulate patient-specific brain activity to assist in:
* **Diagnostic Mapping**: Identifying seizure zones.
* **Therapy Tuning**: Personalizing medical interventions.
* **Co-simulation Technology**: Simultaneously simulating at the full-brain level while maintaining the importance of specific electrode placements (e.g., SEEG) for high-precision results.



## 5. Key Scientific Contributions

The presentation referenced several critical works supporting these advancements:

* **Llinas (2003)**: On the synthesis of brain organization.
* **D’Angelo and Jirsa (TINS 2022)**: On multiscale direct and inverse problems.
* Lorenzi et al. (2023/In Prep): On mean field models and platform development.
* Casali et al. (2020): Regarding cerebellar plasticity and learning theory.

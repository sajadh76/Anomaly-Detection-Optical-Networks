## Overview
Welcome to the Optical Signal Anomaly Detection project! 🌌 This initiative aims to identify anomalies in optical transponder signals by analyzing constellation diagrams, with a specific focus on 16QAM constellations at the receiver of the Channel Under Test (CUT). The goal is to distinguish between normal and faulty signal conditions based on the presence and characteristics of interferers at various power levels and distances from the CUT.

## Dataset
Explore the dataset containing constellation diagrams of the 16QAM receiver at the CUT by following this [link](https://ieee-dataport.org/open-access/constellation-diagrams-spectrum-anomaly-detection-optical-networks). The dataset includes two key components:

### Full Image Dataset (from 2 Different Domains)
- Constellation diagrams of the 16QAM receiver at the CUT.
- Annotated with 5 classes for normal and faulty signal conditions.

### One-Symbol Image Dataset (from 2 Different Domains)
- Extracted from full images, focusing on a single symbol in the 16QAM constellation.
- Allows investigation of localized features and patterns.

## Algorithms
The following algorithms have been used in this project:
- One-Class SVM
- Isolation Forest
- Transfer Learning
- Domain Adaptaion
- Principal Component Analysis (PCA)
- Explainable AI (GradCAM XAI)

## Execution
You can simpy run the code on platforms like Google Colab or Kaggle. 




---
layout: page
title: ""
---

## Research Summary

I am broadly interested in applying data-driven technologies (e.g., machine learning or adaptive state-space modeling), to real-world problems to enhance human capabilities. My experience spans working with various datasets from fields including wearable computing, affective computing, 6D pose estimation, 2D and 3D computer vision, and behavioral driver modeling.

Currently, my research focuses on developing predictive models for wearable devices. Until now this included predicting physiological events, such as exertional heat stroke, and tracking 3D tongue positions using magnetic localization. I also explored disentangled representation learning by using contrastive learning on human activity recognition problem. My ongoing projects involve exploring self-supervised learning strategies for physiological computing, improving magnetic localization for motion tracking, creating algorithms for physiological signal quality indexing and fiducial point prediction. Based on my experience until now, the following factors make these problems especially challenging:

**1. Multi-Modality**: We struggle with understanding how different modalities or signals (e.g., ECG, PPG, and other cardiac signals) interact when we use deep learning models. This lack of understanding complicates debugging and hinders our ability to scientifically uncover the reasons behind a model's decisions. Nonetheless, grasping and utilizing multi-modal connections is crucial. 
**2. Temporal information**: Capturing and analyzing temporal information in sensor data is essential, yet challenging. The temporal aspect adds complexity to data analysis and model development.
**3. Variability**:  Each individual's physiological signals exhibit significant variability due to numerous factors, even within a single person. This variability complicates the development of consistent and accurate algorithms.
**4. Motion artifacts**: Motion can corrupt data, and eliminating these artifacts completely is a non-trivial task. Motion artifacts pose a significant challenge in maintaining data integrity.
**5. Personalization**: The variability between individuals means that parameters extracted from a training dataset often do not generalize well to others. This necessitates a personalization stage, which, although often involving a baseline period, can be difficult to implement in commercial applications.
**6. Online learning**: Physiological parameters change in real time, requiring models to update their parameters dynamically. This need for real-time adaptation adds another layer of complexity to model development and deployment.

During my undergraduate studies, I worked on behavioral human driver modeling, utilizing approaches from game theory, control theory, reinforcement learning, and probabilistic modeling (e.g., multi-output Gaussian processes). I continue to incorporate techniques such as state-space modeling and reinforcement learning into my current research. 

For my upcoming Ph.D. work, I am particularly interested in:
**1**. Developing unsupervised and self-supervised representation learning algorithms for physiological signals, which can be applied to various downstream tasks, instead of task specific algorithm development.
**2**. Uncovering multimodal relationships in wearable signals to better understand and interpret model decisions.
**3**. Integrating state-space models, such as Kalman filters, with deep learning-based representation learning algorithms to model physiological states. This fusion aims to combine the speed and interpretability of state-space models with the expressiveness of deep learning.
**4**. Incorporating human input/feedback into the loop to make these technologies safer and more useful.

*Key areas of my research include:*
- Time series analysis and predictive models
- Wearable/Physiological computing
- Multi-modal data fusion
- Representation learning for sensor data (with temporal, cross-modal relations)
- Anomaly detection
- Magnetic localization for motion tracking

*Key methodological approaches I am utilizing:*
- Machine/deep learning
- Representation learning (self-supervised, contrastive, disentangled, generative etc.)
- Time series analysis
- Signal processing
- State-space modeling (Kalman filters etc.)
- Reinforcement learning
- Computer vision

## Publications
1. **C. O. Yaldiz** and Y. Yildiz, “Driver Modeling Using a Continuous Policy Space: Theory and Traffic Data Validation,” IEEE Transactions on Intelligent Vehicles, 2023.
2. D. J. Lin et al., “Predicting Soldier Performance on Structured Military Training Marches with Wearable Accelerometer and Physiological Data,” IEEE Sensors Journal, 2023.
3. **C. O. Yaldiz** et al., “Early Prediction of Impending Exertional Heat Stroke With Wearable Multimodal Sensing and Anomaly Detection,” IEEE Journal of Biomedical and Health Informatics, 2023.
4. **C. O. Yaldiz**, N. Sebkhi, A. Bhavsar, J. Wang, and O. T. Inan, “Improving Reliability of Magnetic Localization Using Input Space Transformation,” IEEE Sensors Journal, 2023.
5. **C. O. Yaldiz** and Y. Yildiz, “Driver modeling using continuous reasoning levels: A game theoretical approach,” in 2022 IEEE 61st Conference on Decision and Control (CDC), 2022, pp. 5068–5073.



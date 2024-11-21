---
layout: page
title: ""
---

## Research Summary

I am broadly interested in applying data-driven technologies (e.g., machine learning or adaptive state-space modeling), to real-world decision-making problems. My experience spans working with various datasets from fields including wearable computing, psychophysiological computing, real-time systems, affective computing, 2D and 3D computer vision, and behavioral driver modeling.

My PhD research focuses on developing predictive models for wearable devices. To date, my work has included predicting physiological events such as exertional heat stroke, forecasting cardiac event timings (e.g., aortic opening, aortic closing, and R-peaks), and tracking 3D tongue positions using magnetic localization. My ongoing projects explore self-supervised learning strategies for physiological computing, particularly in developing latent spaces for physiological signals using encoder-decoder architectures (e.g., transformers). Additional efforts include signal quality indexing for seismocardiogram (SCG) signals and automated detection of cardiac events in SCG data. My prior work also involved magnetic localization for motion tracking. Throughout my research, I have identified several factors that make these problems particularly challenging:

**1. Multi-Modality**: We struggle with understanding how different modalities or signals (e.g., ECG, PPG, and other cardiac signals) interact when we use deep learning models. This lack of understanding complicates debugging and hinders our ability to scientifically uncover the reasons behind a model's decisions. Nonetheless, grasping and utilizing multi-modal connections is crucial. <br>
**2. Temporal information**: Capturing and analyzing temporal information in sensor data is essential, yet challenging. The temporal aspect adds complexity to data analysis and model development. <br>
**3. Variability**:  Each individual's physiological signals exhibit significant variability due to numerous factors, even within a single person. This variability complicates the development of consistent and accurate algorithms. <br>
**4. Motion artifacts**: Motion can corrupt data, and eliminating these artifacts completely is a non-trivial task. Motion artifacts pose a significant challenge in maintaining data integrity. <br>
**5. Personalization**: The variability between individuals means that parameters extracted from a training dataset often do not generalize well to others. This necessitates a personalization stage, which, although often involving a baseline period, can be difficult to implement in commercial applications. I strongly believe that human-in-the-loop systems, whenever feasible, bridge the gap by enabling control and correction of the system, ultimately making it safer and more reliable for use in clinical settings. <br>
**6. Online learning**: Physiological parameters change in real time, requiring models to update their parameters dynamically. This need for real-time adaptation adds another layer of complexity to model development and deployment. <br>

During my undergraduate studies, I worked on behavioral human driver modeling, utilizing approaches from game theory, control theory, reinforcement learning, and probabilistic modeling (e.g., multi-output Gaussian processes). I continue to incorporate techniques such as state-space modeling and reinforcement learning into my current research. 

For my upcoming Ph.D. work, I am particularly interested in: <br>
**1**. Developing unsupervised and self-supervised representation learning algorithms for physiological signals, which can be applied to various downstream tasks, instead of task specific algorithm development. <br>
**2**. Uncovering multimodal relationships in wearable signals to better understand and interpret model decisions. <br>
**3**. Integrating state-space models, such as Kalman filters, with deep learning-based representation learning algorithms to model physiological states. This fusion aims to combine the speed and interpretability of state-space models with the expressiveness of deep learning. <br>
**4**. Incorporating human input/feedback into the loop to make these technologies safer and more useful. <br>
**5** Building on the success of large language models (LLMs), driven by scaling, my aim is to replicate this progress in wearable computing by developing models trained on diverse physiological datasets. These models would enable the creation of robust, generalized frameworks that can be fine-tuned for specific tasks, enhancing their adaptability and precision. <br>

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
- State-space modeling (ARIMA, Kalman filters etc.)
- Reinforcement learning
- Computer vision


---
layout: page
title: ""
---

## PhD Research Summary

I was broadly interested in applying data-driven technologies (e.g., machine learning or adaptive state-space modeling) to real-world decision-making problems. My experience spanned working with various datasets from fields including wearable computing, psychophysiological computing, real-time systems, affective computing, 2D and 3D computer vision, and behavioral driver modeling.

My Ph.D. research focused on developing predictive models for wearable devices. My work included 1. various forms of physiological and quasi-periodic signal representation learning, 2. physiological event prediction such as exertional heat stroke, 3. physiological forecasting of cardiac event timings (e.g., aortic opening, aortic closing, and R-peaks), and 4. 3D motion tracking using magnetic localization.

My later research focused on developing self-supervised learning methods to build physiological foundation models. The goal was to learn latent representations of physiological signals that could generalize across a range of downstream tasks. In essence, this involved discovering data-driven patterns in quasi-periodic signals that capture their morphological characteristics for deeper physiological analysis. Additionally, I explored cross-modal relationships among different biosignals—examining the interactions between brain activity (EEG) and cardiac signals (ECG, SCG, and PPG).

Throughout my research, I identified several factors that made these problems particularly challenging:

**1. Multi-Modality**: We struggle with understanding how different modalities or signals (e.g., ECG, PPG, and other cardiac signals) interact when we use deep learning models. This lack of understanding complicates debugging and hinders our ability to scientifically uncover the reasons behind a model's decisions. Nonetheless, grasping and utilizing multi-modal connections is crucial. <br>
**2. Temporal information**: Capturing and analyzing temporal information in sensor data is essential, yet challenging. The temporal aspect adds complexity to data analysis and model development. <br>
**3. Variability**: Each individual's physiological signals exhibit significant variability due to numerous factors, even within a single person. This variability complicates the development of consistent and accurate algorithms. <br>
**4. Motion artifacts**: Motion can corrupt data, and eliminating these artifacts completely is a non-trivial task. Motion artifacts pose a significant challenge in maintaining data integrity. <br>
**5. Personalization**: The variability between individuals means that parameters extracted from a training dataset often do not generalize well to others. This necessitates a personalization stage, which, although often involving a baseline period, can be difficult to implement in commercial applications. I strongly believed that human-in-the-loop systems, whenever feasible, bridged the gap by enabling control and correction of the system, ultimately making it safer and more reliable for use in clinical settings. <br>
**6. Online learning**: Physiological parameters change in real time, requiring models to update their parameters dynamically. This need for real-time adaptation adds another layer of complexity to model development and deployment. <br>
**7. Data Scarcity**: Unfortunately, large-scale datasets encompassing thousands of participants are rarely available in this field. This limitation, compounded by the high noise levels typically present in smaller datasets, makes it challenging to depend solely on model complexity or scale. <br>

During my undergraduate studies, I worked on behavioral human driver modeling, utilizing approaches from game theory, control theory, reinforcement learning, and probabilistic modeling (e.g., multi-output Gaussian processes). I continued to incorporate techniques such as state-space modeling and reinforcement learning into my research throughout my Ph.D.

Looking back, some of the open questions I found myself curious about, and which I left for future exploration, included: <br>
**1**. Could representation learning algorithms for physiological signals (e.g., brain and cardiac signals) be developed in a way that generalized across various downstream tasks (e.g., foundation models), rather than relying on task-specific algorithm development? <br>
**2**. How might multimodal relationships in wearable signals be uncovered to better understand and interpret model decisions? <br>
**3**. How could human input and feedback be incorporated into the loop to make these technologies safer and more useful? <br>
**4**. Building on the success of large language models (LLMs), driven by scaling, could similar progress be replicated in wearable computing by developing models trained on diverse physiological datasets? Could such models enable the creation of robust, generalized frameworks that could be fine-tuned for specific tasks, enhancing their adaptability and precision? <br>

*Key areas of my research included:*
- Time series analysis and predictive models
- Wearable/Physiological computing
- Multi-modal data fusion
- Representation learning for sensor data (with temporal, cross-modal relations)
- Anomaly detection
- Magnetic localization for motion tracking

*Key methodological approaches I utilized:*
- Machine/deep learning
- Representation learning (self-supervised, contrastive, disentangled, generative etc.)
- Time series analysis
- Signal processing
- State-space modeling (ARIMA, Kalman filters etc.)
- Reinforcement learning
- Computer vision


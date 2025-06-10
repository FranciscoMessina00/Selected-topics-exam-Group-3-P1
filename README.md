# Selected-topics-exam-Group-3-P1
Classifying environmental audio is a challenging yet increasingly relevant task within the broader field of machine learning for audio analysis. The aim of this project is to develop and evaluate a system that can automatically categorize short, isolated audio recordings into a set of predefined classes. These classes represent a wide variety of everyday sounds, such as animal noises, human activities, natural phenomena, and urban environments.

This problem sits at the intersection of signal processing and machine learning and has practical applications in a range of domains, including smart surveillance, context-aware systems, sound event detection, and interactive technologies. Automatically recognizing sound categories from short clips can enable more responsive and intelligent systems in real-world settings.

To address this task, the project adopts an exploratory approach that investigates multiple stages of the audio classification pipeline. Particular emphasis is placed on audio preprocessing and representation, where two time-frequency transformations—Mel spectrograms and MFCCs—are tested to extract informative features from raw waveform data. These representations are critical, as they determine how well the model can capture the relevant spectral and temporal characteristics of different sound events.

Another core aspect of the approach is data augmentation. Since real-world audio can vary widely due to background noise, microphone quality, or environmental conditions, it is important to simulate such variability during training. Augmentation techniques such as time masking, frequency masking, and background noise addition are applied to improve the model’s robustness and generalization, particularly in low-data regimes.

Ultimately, the goal is to implement a reliable and reproducible classification pipeline that takes a short audio clip as input and outputs the predicted sound category with high accuracy. Along the way, the influence of design choices—including feature extraction methods, model architectures, and augmentation strategies—is critically assessed to gain deeper insight into what contributes most to performance.

## Attention!
If cloning this repository, verify that the checkpoints are cloned correctly, it may happen that they are not downloaded correctly. If it happens, download them individually.

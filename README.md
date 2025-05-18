🧭 Overview
This project explores the use of a Multi-Layer Perceptron (MLP) as the foundational scene representation in a Simultaneous Localization and Mapping (SLAM) system. The design incorporates a keyframe-based framework and evaluates positional encoding versus Gaussian encoding for spatial representation fidelity. The system is deployed on an F1/10th-scale autonomous vehicle to enable real-time localization in previously unseen environments. Notably, the MLP dynamically builds a dense map without relying on prior data, leveraging visual input to update the scene in real time.

🚗 Key Contributions
Lightweight MLP-Based SLAM System: Engineered a 4-layer MLP-based SLAM system, achieving a 50% reduction in model complexity compared to NeRF-style volumetric mapping approaches.

Adaptive Keyframe Selection: Designed and implemented an adaptive keyframe selection algorithm, reducing the number of processed frames by 73.8% (from 2869 to 750), significantly improving efficiency.

Active Sampling Strategies: Integrated active sampling strategies to optimize computational load and enhance image reconstruction accuracy, enabling real-time performance on embedded platforms.

🛠️ Technical Highlights
Scene Representation: Utilizes a 4-layer MLP as the sole scene representation, dynamically building a dense map without prior data.

Encoding Techniques: Evaluates positional encoding versus Gaussian encoding to determine the most effective method for spatial representation fidelity.

Real-Time Deployment: Successfully deployed the system on an F1/10th-scale autonomous vehicle, demonstrating real-time localization in previously unseen environments.

![image](https://github.com/user-attachments/assets/8ea6404c-9b33-47fa-a75d-6b7752880f61)



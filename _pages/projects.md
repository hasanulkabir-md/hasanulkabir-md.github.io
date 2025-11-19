---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---

Here is a selection of my main projects. More details are available on my GitHub and research pages.

---

## Video-based Obstacle Avoidance using Deep Reinforcement Learning (DRL)

![Video-based obstacle avoidance thumbnail](/images/projects/drl-obstacle-avoidance.jpg){: width="260" .align-left }

This ongoing research focuses on developing an intelligent obstacle avoidance system for autonomous mobile robots using real-time video input.  
A **YOLO-based object detection** model is used to detect and classify dynamic obstacles, while **DRL algorithms (DQN, PPO)** learn navigation strategies through continuous interaction with the environment.

The system is developed and tested in **ROS** and **Gazebo**, allowing experiments under different lighting conditions, sensor noise, and motion dynamics.  
The goal is an end-to-end framework that tightly fuses **visual perception** and **decision-making** for safer and more robust autonomous navigation.

{: .clear }

---

## Kalman Filter for Motion Tracking

![Kalman filter thumbnail](/images/projects/kalman-filter-tracking.jpg){: width="260" .align-left }

A project demonstrating how **probabilistic filtering** can recover smooth motion estimates from noisy sensor data.

- **Problem:** Position sensors often produce jittery, unreliable readings during robot motion.  
- **Method:** Implemented a 2D **Kalman Filter** combining a constant-velocity motion model with noisy position measurements.  
- **Result:** Achieved smooth, noise-reduced trajectories and accurate velocity estimates, improving tracking stability for robotics and navigation.

**Keywords:** State Estimation, Sensor Fusion, Robotics, Applied Mathematics

{: .clear }

---

## Bayesian Regression for Noisy Sensor Data

![Bayesian regression thumbnail](/images/projects/bayesian-regression-sensors.jpg){: width="260" .align-left }

A probabilistic modeling project focusing on **uncertainty in real-world sensor readings**.

- **Problem:** Standard linear regression provides point estimates but no confidence in predictions.  
- **Method:** Built a **Bayesian linear regression** framework to simulate sensor readings and compute predictive distributions with credible intervals.  
- **Result:** Generated interpretable predictions with quantified uncertainty, improving trust and decision reliability in sensor-based systems.

**Keywords:** Bayesian Inference, Uncertainty Quantification, Applied Machine Learning

{: .clear }

---

## Classifying Fashion-MNIST Images with CNNs

![Fashion MNIST CNN thumbnail](/images/projects/fashion-mnist-cnn.jpg){: width="260" .align-left }

A **Convolutional Neural Network (CNN)** to classify clothing items in the **Fashion-MNIST** dataset.

- Normalized and split the dataset into training, validation, and test sets  
- Designed a custom CNN architecture trained with the **Adam** optimizer and **sparse categorical cross-entropy** loss  
- Achieved around **90.66% accuracy** on the test set

This project strengthens my foundations in deep learning, experiment tracking, and model evaluation.

{: .clear }

---

## Attention-Enhanced Spatio-Temporal GCN for Air Quality Prediction

![Air quality AE-STGCN thumbnail](/images/projects/ae-stgcn-air-quality.jpg){: width="260" .align-left }

Air pollution is a major challenge in rapidly industrializing regions. Accurate forecasting of air quality is important for policy and health protection.

This project proposes an **Attention-Enhanced Spatio-Temporal Graph Convolutional Network (AE-STGCN)** that:

- Fuses heterogeneous data: pollutant measurements, meteorological variables, and POI information  
- Builds a grid-based graph representation of urban regions  
- Uses spatial–temporal attention to learn which regions and time intervals are most important

The result is a model with improved predictive accuracy and better interpretability for air quality forecasting.

{: .clear }



## Multi-point Navigation for Intelligent Inspection Robots
Research project related to your published paper.

- Designs a navigation method to visit multiple waypoints efficiently  
- Implemented and tested in a simulated inspection robot platform  
- Co-authored a paper in *Journal of Computing & Electronic Information Management, 2024*

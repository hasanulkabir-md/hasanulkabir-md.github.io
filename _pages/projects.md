---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---

Here is a selection of my main projects. More details are available on my GitHub and research pages.

---

## Video-based Obstacle Avoidance using Deep Reinforcement Learning (DRL)

<div style="display: flex; align-items: flex-start; margin-bottom: 16px;">
  <img src="/images/drl-obstacle-avoidance.jpg"
       alt="Video-based obstacle avoidance thumbnail"
       style="width:110px; margin-right:15px; border-radius:6px;">
  <div>
    This ongoing research focuses on developing an intelligent obstacle avoidance system for
    autonomous mobile robots using real-time video input.<br><br>
    A <strong>YOLO-based object detection</strong> model is used to detect and classify dynamic
    obstacles, while <strong>DRL algorithms (DQN, PPO)</strong> learn navigation strategies
    through continuous interaction with the environment.<br><br>
    The system is developed and tested in <strong>ROS</strong> and <strong>Gazebo</strong>,
    allowing experiments under different lighting conditions, sensor noise, and motion dynamics.
    The goal is an end-to-end framework that tightly fuses <strong>visual perception</strong>
    and <strong>decision-making</strong> for safer and more robust autonomous navigation.
  </div>
</div>

---

## Kalman Filter for Motion Tracking

<div style="display: flex; align-items: flex-start; margin-bottom: 16px;">
  <img src="/images/kalman-filter-tracking.jpg"
       alt="Kalman filter tracking thumbnail"
       style="width:110px; margin-right:15px; border-radius:6px;">
  <div>
    A project demonstrating how <strong>probabilistic filtering</strong> can recover smooth motion
    estimates from noisy sensor data.<br><br>
    <strong>Problem:</strong> Position sensors often produce jittery, unreliable readings during robot motion.<br>
    <strong>Method:</strong> Implemented a 2D <strong>Kalman Filter</strong> combining a constant-velocity
    motion model with noisy position measurements.<br>
    <strong>Result:</strong> Achieved smooth, noise-reduced trajectories and accurate velocity estimates,
    improving tracking stability for robotics and navigation.<br><br>
    <strong>Keywords:</strong> State Estimation, Sensor Fusion, Robotics, Applied Mathematics
  </div>
</div>

---

## Bayesian Regression for Noisy Sensor Data

<div style="display: flex; align-items: flex-start; margin-bottom: 16px;">
  <img src="/images/bayesian-regression-sensors.jpg"
       alt="Bayesian regression thumbnail"
       style="width:110px; margin-right:15px; border-radius:6px;">
  <div>
    A probabilistic modeling project focusing on <strong>uncertainty in real-world sensor readings</strong>.<br><br>
    <strong>Problem:</strong> Standard linear regression provides point estimates but no confidence in predictions.<br>
    <strong>Method:</strong> Built a <strong>Bayesian linear regression</strong> framework to simulate sensor
    readings and compute predictive distributions with credible intervals.<br>
    <strong>Result:</strong> Generated interpretable predictions with quantified uncertainty, improving trust and
    decision reliability in sensor-based systems.<br><br>
    <strong>Keywords:</strong> Bayesian Inference, Uncertainty Quantification, Applied Machine Learning
  </div>
</div>

---

## Classifying Fashion-MNIST Images with CNNs

<div style="display: flex; align-items: flex-start; margin-bottom: 16px;">
  <img src="/images/fashion-mnist-cnn.jpg"
       alt="Fashion MNIST CNN thumbnail"
       style="width:110px; margin-right:15px; border-radius:6px;">
  <div>
    A <strong>Convolutional Neural Network (CNN)</strong> to classify clothing items in the
    <strong>Fashion-MNIST</strong> dataset.<br><br>
    - Normalized and split the dataset into training, validation, and test sets<br>
    - Designed a custom CNN architecture trained with the <strong>Adam</strong> optimizer and
      <strong>sparse categorical cross-entropy</strong> loss<br>
    - Achieved around <strong>90.66% accuracy</strong> on the test set<br><br>
    This project strengthens my foundations in deep learning, experiment tracking, and model evaluation.
  </div>
</div>

---

## Attention-Enhanced Spatio-Temporal GCN for Air Quality Prediction

<div style="display: flex; align-items: flex-start; margin-bottom: 16px;">
  <img src="/images/ae-stgcn-air-quality.jpg"
       alt="AE-STGCN air quality thumbnail"
       style="width:110px; margin-right:15px; border-radius:6px;">
  <div>
    Air pollution is a major challenge in rapidly industrializing regions. Accurate forecasting of air
    quality is important for policy and health protection.<br><br>
    This project proposes an <strong>Attention-Enhanced Spatio-Temporal Graph Convolutional Network (AE-STGCN)</strong> that:<br>
    - Fuses heterogeneous data: pollutant measurements, meteorological variables, and POI information<br>
    - Builds a grid-based graph representation of urban regions<br>
    - Uses spatial–temporal attention to learn which regions and time intervals are most important<br><br>
    The result is a model with improved predictive accuracy and better interpretability for air quality forecasting.
  </div>
</div>

---

## Multi-point Navigation for Intelligent Inspection Robots

<div style="display: flex; align-items: flex-start; margin-bottom: 16px;">
  <img src="/images/inspection-thumb.jpg"
       alt="Inspection robot navigation thumbnail"
       style="width:110px; margin-right:15px; border-radius:6px;">
  <div>
    Research project related to my journal publication on intelligent inspection robots.<br><br>
    - Designs a navigation method to visit multiple waypoints efficiently<br>
    - Implemented and tested in a simulated inspection robot platform<br>
    - Co-authored a paper in <em>Journal of Computing &amp; Electronic Information Management</em>, 2024
  </div>
</div>

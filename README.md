# Robotic programming by imitation: haptic devices and machine learning to recognize user actions.

<img width="514" height="389" alt="TCN_pipeline" src="https://github.com/user-attachments/assets/72cafa58-7efa-4e40-80bb-2a0905b58542" />

This repository is a fork of the [Domain-and-View-point-Agnostic-Hand-Action-Recognition](https://github.com/LucaFilippetti99/Domain-and-View-point-Agnostic-Hand-Action-Recognition) project, extended for my MSc thesis at Politecnico di Torino. It adapts hand action recognition to control robot movements via real-time pose estimation and Unity streaming.

## Project Overview

The original project focuses on domain- and viewpoint-agnostic recognition of hand actions using RGB-D data and 3D poses. My thesis expands this to a full pipeline for robot teleoperation: hand actions detected with MANUS gloves drive a Unity-simulated robot arm.

Key motivations include bridging egocentric hand tracking with robotic control in AR/XR environments, tested in industrial scenarios like PCB debugging.

## New Contributions

- **Custom MANUS Dataset**: Recorded 10+ action sequences (e.g., grasp, point, wave) using MANUS Prime gloves in varied lighting/views. Dataset includes synchronized VR hand poses, RGB videos, and annotations (~5k frames).

- **Code Modifications**:
  - Updated pose extraction for MANUS VR data streams.
  - Integrated real-time inference with OpenCV for 30fps processing.

- **Unity Integration**: Standalone Unity project (to be added). Supports WebRTC for low-latency teleop.

<img width="1319" height="275" alt="RT_pipeline" src="https://github.com/user-attachments/assets/ab405b1b-7485-4c46-9e4d-a3b6bcc3ef43" />


## Pipeline

<img width="1580" height="360" alt="myPipeline" src="https://github.com/user-attachments/assets/35531497-b486-4501-818c-54073f0c2245" />




# Real-Time Multi-Camera Intelligent Vision System (Edge AI)

This repository contains the system design, configuration artifacts, and deployment scaffolding
for a real-time multi-camera intelligent vision system designed for industrial environments.

## Objective
Design a production-ready edge AI vision system under strict constraints of latency (<50ms),
power, memory, and reliability, using NVIDIA Jetson platforms.

## Key Capabilities
- Object Detection (YOLOv8 + TensorRT)
- Semantic Segmentation (DeepLabV3+)
- Video Analytics (Tracking, Counting, Anomaly Detection)
- Image Stitching / 3D Reconstruction
- Unsupervised Pattern Discovery (DBSCAN)

## Target Hardware
- NVIDIA Jetson Xavier NX / Orin Nano
- Optional: Raspberry Pi with accelerator

## NVIDIA Stack
- DeepStream (multi-stream pipeline)
- TAO Toolkit (transfer learning)
- TensorRT (FP16 / INT8 inference)

## Repository Structure
- docs/ – Final PDF solution and architecture diagram
- deepstream/ – DeepStream pipeline and inference configs
- docker/ – Containerization setup
- scripts/ – Optimization and TensorRT build scripts

## Notes
This repository focuses on system architecture and production design,
as expected for a hiring assignment.

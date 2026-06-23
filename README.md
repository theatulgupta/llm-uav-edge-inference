# LLM-Guided UAV Edge Inference

> M.Tech Thesis Project: LLM-Guided Neural Network Compilation for Real-time UAV Edge Inference

## Overview

This research explores the use of Large Language Models (LLMs) as intelligent optimization agents for deploying deep neural networks on resource-constrained UAV edge devices.

The goal is to automatically analyze neural network models, generate optimization strategies, and improve real-time inference performance on embedded platforms such as NVIDIA Jetson.

## Research Objectives

- Analyze neural network architectures using LLMs.
- Automatically generate model optimization strategies.
- Optimize models for real-time UAV deployment.
- Benchmark LLM-guided optimizations against manual optimization techniques.
- Evaluate inference latency, throughput, and resource utilization.

## Proposed System Architecture

```text
Neural Network Model
          ↓
     LLM Analyzer
          ↓
 Optimization Strategy
          ↓
 Model Compilation
          ↓
 Edge Deployment (Jetson)
          ↓
 Real-Time UAV Inference
```

## Technology Stack

- Python
- PyTorch
- ONNX
- TensorRT
- NVIDIA Jetson
- ROS2
- PX4
- Gazebo
- Large Language Models (LLMs)

## Repository Structure

```text
.
├── docs/                 # Notes, papers, documentation
├── experiments/          # Experimental results
├── models/               # Neural network models
├── optimization/         # LLM-generated optimizations
├── deployment/           # Jetson deployment scripts
├── simulation/           # PX4 + ROS2 + Gazebo setup
├── benchmarks/           # Performance benchmarks
├── notebooks/            # Jupyter notebooks
└── src/                  # Source code
```

## Research Questions

1. Can LLMs act as intelligent neural network compilers?
2. Can automatically generated optimizations improve edge inference performance?
3. How do LLM-guided optimizations compare with manual optimization techniques?
4. What is the impact on real-time UAV applications?

## Current Status

- [x] Literature Survey
- [x] PX4 + ROS2 + Gazebo Setup
- [ ] LLM Optimization Pipeline
- [ ] Jetson Deployment
- [ ] Benchmarking Framework
- [ ] Experimental Evaluation

---

**Author:** Atul Kumar Gupta  
**Degree:** M.Tech, Computer Science & Engineering  
**Institute:** PDPM IIITDM Jabalpur

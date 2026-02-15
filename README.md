
# 3D Reconstruction without Camera Parameters

This project explores modern computer vision techniques for reconstructing 3D scenes
from ordinary 2D images where camera calibration is unknown.

The work  focuses on understanding how recent learning-based methods overcome limitations of traditional geometry-based
reconstruction.

---

## Problem

Most classical 3D reconstruction methods require:
- Multiple calibrated camera views
- Known camera positions
- Structured capture setup

In real-world scenarios (mobile photos, internet images), this information is not available.

The goal is to reconstruct 3D structure directly from unstructured images.

---

## Methods Studied

### Neural Radiance Fields (NeRF)
Learns a continuous 3D representation using neural networks to synthesize novel views.

### Point-based Reconstruction
Uses sparse 3D point clouds to approximate scene geometry.

### Mesh-based Models
Creates surface meshes from estimated geometry.

### 3D Gaussian Splatting
Fast real-time rendering using explicit Gaussian primitives instead of implicit neural fields.

### SAMURAI Framework
Jointly estimates:
- Shape
- Material
- Lighting
- Camera pose

from unconstrained images.

---

## Key Learning Outcomes

- Understanding camera-free reconstruction pipelines
- Training behavior of neural rendering models
- Effect of iteration count on convergence
- Tradeoff between NeRF quality and Gaussian Splatting speed

---

## Results
Coming Soon

(Visual outputs and comparisons will be added)

---



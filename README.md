# CogVideoX-5b-i2v Physics-IQ Benchmark

This repository contains **all artifacts required to reproduce Physics-IQ–style benchmarking for CogVideoX**, including evaluation scripts, generated samples, and results.

---

##  Overview

Physics-IQ benchmarks aim to evaluate a video generation model’s **physical reasoning and temporal consistency**, such as:

* Object permanence
* Gravity and motion consistency
* Cause–effect relationships
* Temporal coherence across frames

This repository applies that evaluation protocol to **CogVideoX**.

>  **Important**: This benchmark is intended for *informational and comparative analysis*. It does **not** claim state-of-the-art performance.

---

##  Environment & Requirements

### Hardware (Recommended)

Running CogVideoX reliably for this benchmark requires **significant compute**:

* **GPU**: NVIDIA H100
* **VRAM**: ≥ 40GB (minimum), 80GB recommended
* **RAM**: ≥ 64GB
* **Disk**: ≥ 100GB free (videos + intermediate artifacts)

> Lower-end GPUs may run out of memory or require aggressive offloading.

---

### Software

* Python **3.10+**
* CUDA-compatible PyTorch
* ffmpeg / ffprobe
* Jupyter Notebook

---

### Video Generation

* Videos are generated using **CogVideoX-5b-I2V**
* Outputs are saved as `.mp4`
* Frame rate and resolution are kept consistent across runs

---


##  Results

Achieved a physics-IQ-benchmark of **32.3%**


---

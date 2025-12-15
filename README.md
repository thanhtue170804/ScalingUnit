##  Block Diagram
<img width="1231" height="311" alt="image" src="https://github.com/user-attachments/assets/e1684148-fa99-4254-9227-5bd22107331d" />
# Pipelined Scaling & Quantization Unit 📉
**Hardware Accelerator for Neural Network Post-Processing**

## 📌 Overview
This repository contains a **SystemVerilog** implementation of a configurable **Scaling Unit** designed for fixed-point arithmetic. It is commonly used in **Deep Learning Accelerators (NPU)** to quantize 32-bit accumulation results back to 8-bit integers (int8) for activation functions or memory storage.

The design features a **3-stage pipeline** to maximize throughput and includes robust handling for **Rounding** and **Saturation**.


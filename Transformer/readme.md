# Human Activity Recognition with Smartphones 📱🏃‍♂️

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![PyTorch](https://img.shields.io/badge/PyTorch-1.9+-ee4c2c.svg)](https://pytorch.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository implements a **Transformer Encoder Network** for classifying human activities using the **UCI Human Activity Recognition (HAR) Dataset**. The model processes time‑series data from smartphone accelerometers and gyroscopes to distinguish between six daily activities.

---

## ✨ Features

- End‑to‑end pipeline: data loading, preprocessing, training, and evaluation.
- Transformer encoder architecture with multi‑head self‑attention for sequential sensor data.
- Supports GPU acceleration (CUDA).
- Configurable hyperparameters (sequence length, embedding dimension, number of heads, etc.).
- Visualisation of training curves and confusion matrices.

---

## 📊 Dataset

**UCI HAR Dataset**  
- 30 volunteers aged 19–48 performed six activities while wearing a Samsung Galaxy S II on the waist.
- **Sensor signals**: 3‑axis linear acceleration (total + body) and 3‑axis angular velocity (gyroscope) at 50 Hz.
- **Preprocessed data**: Fixed‑width sliding windows (2.56 sec, 50% overlap) → 128 readings per window.
- **Activities**:
  - Walking 🚶
  - Walking Upstairs 🚶‍♂️⬆️
  - Walking Downstairs 🚶‍♂️⬇️
  - Sitting 🪑
  - Standing 🧍
  - Laying 🛌

> **Download**  
> The dataset is not included in this repository. You can obtain it from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/240/human+activity+recognition+using+smartphones).  
> Place the `UCI HAR Dataset` folder in the project root before running the code.

---

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/human-activity-recognition-transformer.git
   cd human-activity-recognition-transformer
   

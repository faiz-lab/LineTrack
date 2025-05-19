# LineTrack

> A research project for analyzing assembly line operations using MS-TCN and self-supervised learning.

流水线动作识别项目，用于修士课题研究。
目录结构已初始化，可根据需要填充代码和数据。

This project aims to recognize and segment worker actions from factory video data. It combines temporal convolutional networks (MS-TCN) and contrastive self-supervised learning to minimize annotation effort while achieving reliable performance.

## 📁 Project Structure

- `data/`: videos, annotations, and features
- `models/`: trained model checkpoints
- `scripts/`: training & inference code
- `configs/`: configuration YAML files
- `results/`: prediction outputs & charts

## 🚀 Goals

- Analyze line-based manual operations
- Reduce labeling cost using self-supervised pretraining
- Demonstrate effective action segmentation with MS-TCN

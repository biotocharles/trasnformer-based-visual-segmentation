# Transformer-Based Visual Segmentation

Implementation of transformer-based architectures for semantic, instance, and panoptic segmentation tasks, inspired by the paper **"Transformer-Based Visual Segmentation: A Survey"**.

## 🚀 Overview

This project explores and compares the performance of modern Transformer-based models with traditional CNN-based models in the domain of visual segmentation.

### 📌 Tasks Covered:
- **Semantic Segmentation**
- **Instance Segmentation**
- **Panoptic Segmentation**

### 🔍 Models Implemented:
- **SegFormer** (Transformer-based Semantic Segmentation)
- **Mask2Former** (Universal Segmentation with Transformer backbone)
- **DeepLabV3** (CNN-based baseline)
- **Mask R-CNN** (CNN-based Instance Segmentation)

---

## 🛠️ Tech Stack

- **Python 3.9+**
- **PyTorch**
- **Hugging Face Transformers**
- **Detectron2**
- **Google Colab**
- **COCO Dataset**

---

## 📂 Project Structure

```bash
transformer-visual-segmentation/
│
├── semantic_segmentation/
│   ├── segformer_inference.py
│   ├── deeplabv3_baseline.py
│
├── instance_segmentation/
│   ├── mask2former_instance.py
│   ├── mask_rcnn_baseline.py
│
├── panoptic_segmentation/
│   ├── mask2former_panoptic.py
│   ├── panoptic_fpn.py
│
├── utils/
│   ├── visualization.py
│   ├── metrics.py
│
├── outputs/
│   └── predictions/  # Stores sample output images
│
├── requirements.txt
└── README.md

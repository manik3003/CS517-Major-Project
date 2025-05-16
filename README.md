# CS517-Major-Project - DeHaDo-AI Challenge

This project is part of the **CS517 Major Project** course and aims to solve the DeHaDo-AI Challenge — a document understanding task involving handwritten application forms. The goal is to extract structured data in the form of field names, values, and their bounding box coordinates from scanned images of handwritten forms.

---

## 🔗 Challenge and Dataset

- **Challenge Website**: [DeHaDo-AI Challenge](https://sites.google.com/view/dehado-ai/home?authuser=0)
- **Dataset Download**: [Google Drive Link](https://drive.google.com/file/d/17lcMfsRrlfBVkWdfm2ESP9DN6tczXo-E/view?usp=sharing)
- **Baseline YOLOv8 Weights**: [Download YOLOv8 Weights](https://drive.google.com/file/d/1M686XZh5rJ42Y87m386EKlM-h2SgiXXg/view?usp=drive_link)

---

## 📁 Directory Structure

```plaintext
CS517-Major-Project/
├── dataset/
│   ├── images/              # All JPG images of forms
│   └── labels/              # JSON files containing annotations
├── notebooks/
│   ├── training_yolo.ipynb  # YOLOv8 training script for the dataset
│   └── final_model.ipynb    # End-to-end pipeline: preprocessing, training, and inference
├── weights/
│   └── yolov8_baseline.pt   # Pre-trained YOLOv8 model
├── utils/
│   ├── json_to_yolo.py      # Convert annotation JSONs to YOLO format
│   └── evaluation.py        # Evaluation metrics
├── requirements.txt
└── README.md

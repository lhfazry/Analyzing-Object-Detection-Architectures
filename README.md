# Analyzing Object Detection Architectures

This repository contains the presentation slides from the webinar focusing on the technical deep-dive of modern Object Detection architectures. It covers the evolution, mechanics, and comparative analysis of state-of-the-art models like Faster R-CNN, SSD, and the YOLO family.

## 📄 Content Overview

The presentation file **`Analyzing Object Detection Architectures.pdf`** provides a comprehensive breakdown of the following topics:

### 1. Foundations of Object Detection
- **Region Proposals:** From brute-force Sliding Window to Selective Search.
- **The Evolution:** R-CNN $\rightarrow$ Fast R-CNN $\rightarrow$ Faster R-CNN.
- **ROI Mechanisms:** Understanding the critical difference between **ROI Pooling** (Quantization) and **ROI Align** (Bilinear Interpolation).

### 2. One-Stage Detectors (YOLO & SSD)
- **The Grid System:** How YOLO assigns objects to specific grid cells.
- **Anchor Boxes:** Handling multiple objects and aspect ratios per cell.
- **SSD (Single Shot MultiBox Detector):** The concept of Multi-Scale Feature Maps (detecting objects at different network depths).

### 3. Backbone Architectures
- **ResNet vs. Darknet:** Why YOLO prefers Darknet (Stride 2) over ResNet (Max Pooling) for real-time speed.
- **Evolution of YOLO Backbones:**
  - **Darknet-53 (YOLOv3):** Residual connections.
  - **CSPNet (YOLOv4/v5):** Splitting gradient paths to reduce redundancy.
  - **E-ELAN (YOLOv7):** Expand, Shuffle, and Merge cardinality.
  - **C2f Module (YOLOv8):** Rich gradient flow design.

### 4. Post-Processing & Optimization
- **Non-Maximum Suppression (NMS):** The algorithm for filtering duplicate bounding boxes using IoU thresholds.
- **Speed vs. Accuracy Trade-off:** When to use Two-Stage vs. One-Stage detectors.

## 🔗 How to Cite

If you find these materials useful for your research or study, please cite this repository:

**APA Style:**
> Fazry, L. (2026). *Analyzing Object Detection Architectures*. GitHub. https://github.com/lhfazry/Analyzing-Object-Detection-Architectures

**BibTeX:**
```bibtex
@misc{fazry2026analyzing,
  author = {Fazry, Lhuqita},
  title = {Analyzing Object Detection Architectures},
  year = {2026},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{[https://github.com/lhfazry/Analyzing-Object-Detection-Architectures](https://github.com/lhfazry/Analyzing-Object-Detection-Architectures)}}
}

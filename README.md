# 🛰️ Multi-Scale Context-Aware Feature Integration for Remote Sensing Segmentation

## 📌 Overview
This project focuses on **context-aware multi-scale feature integration** for **instance segmentation in remote sensing images**. The goal is to enhance segmentation accuracy by leveraging **multi-scale context aggregation**, enabling **more precise object boundaries** and **improved segmentation performance**. The proposed model is compared against **CATNet**, **DeepLabV3**, and **HRNet** on multiple remote sensing datasets.

---

## 🏗️ Models Used
- **CATNet** – The baseline model for instance segmentation.
- **Proposed Model** – A novel approach based on **DeepLabV3** with enhanced multi-scale feature integration.
- **HRNet** – A high-resolution network used for performance benchmarking.

---

## 📂 Datasets
The segmentation models are trained and evaluated on the following **remote sensing datasets**:
- **iSAID** – Instance Segmentation in Aerial Images Dataset.
- **NWPU VHR-10** – Very High-Resolution Remote Sensing Dataset.
- **DIOR** – Dataset for Object Detection in Optical Remote Sensing Images.
- **HRSID** – High-Resolution Ship Detection Dataset.

---

## ⚙️ Methodology
1️⃣ **Preprocessing** – Image normalization, resizing, and annotation conversion.
2️⃣ **Feature Extraction** – Multi-scale context-aware feature aggregation.
3️⃣ **Segmentation Pipeline**:
   - **Baseline**: CATNet.
   - **Proposed Model**: DeepLabV3 with enhanced multi-scale fusion.
   - **Comparison**: HRNet for performance benchmarking.
4️⃣ **Evaluation Metrics**:
   - **IoU (Intersection over Union)** – Measures overlap between predicted and ground truth masks.
   - **mAP (Mean Average Precision)** – Evaluates object detection accuracy.
   - **Dice Coefficient** – Measures segmentation accuracy based on overlap ratio.

---

## 📊 Results & Comparisons
The proposed model demonstrates **higher segmentation accuracy** than CATNet and HRNet across multiple datasets, confirming the effectiveness of **multi-scale feature integration**. Improvements were observed in **IoU, mAP, and Dice Coefficient scores**, making it a **more robust approach for remote sensing segmentation**.

---

## 📌 Conclusion
This project presents an optimized segmentation approach using **DeepLabV3-based context-aware feature aggregation**. The experimental results confirm superior segmentation performance compared to existing models in **remote sensing applications**, making it suitable for tasks like **aerial image analysis, urban planning, and environmental monitoring**.

---

## 🛠️ Technologies Used
🔹 **Python** – TensorFlow, PyTorch, OpenCV.
🔹 **Deep Learning** – CNN-based segmentation models.
🔹 **Remote Sensing Datasets** – iSAID, NWPU, DIOR, HRSID.
🔹 **Evaluation Metrics** – Accuracy, Precision, Recall, IoU, Dice Coefficient.

---

## 📜 License  
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.  

---

🚀 *This project contributes to advancing remote sensing segmentation techniques, optimizing feature integration for enhanced image analysis.*

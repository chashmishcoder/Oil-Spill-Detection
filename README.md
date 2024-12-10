# 🌊 Oil Spill Detection with AIS and Satellite Imagery 🛰️

### Overview
This project presents an advanced solution for detecting marine oil spills, leveraging **Automatic Identification System (AIS)** data and **Sentinel-1 SAR satellite imagery**. By combining vessel anomaly detection with deep learning-based image segmentation, we aim to enable rapid, accurate, and automated oil spill monitoring for environmental preservation.

---

## 📋 Features
- **Real-Time Anomaly Detection:**
  - AIS data clustering using DBSCAN to identify abnormal vessel behavior.
- **Oil Spill Segmentation:**
  - U-Net-based semantic segmentation of satellite imagery for precise oil spill localization.
- **Integrated Framework:**
  - Dual-polarized SAR data processing for enhanced accuracy.
  - Dual-stage validation using AIS and satellite data.

---

## 🚀 Methodology
1. **Anomaly Detection:**
   - Extracted AIS features (SOG, COG, etc.) and applied DBSCAN clustering.
   - Identified anomalies such as erratic vessel behavior indicating potential spills.
2. **Image Segmentation:**
   - Preprocessed Sentinel-1 SAR images.
   - Used U-Net for pixel-wise classification of oil spills.
3. **Validation and Alerts:**
   - Correlated AIS anomalies with segmented regions.
   - Generated alerts for confirmed oil spill incidents.

---

## 🔬 Results
- Precision, Recall, and F1-Score: **1.00** (exceptional balance and accuracy).
- IoU and AUC metrics demonstrate robust segmentation performance.
- Seamless integration of AIS and SAR data for comprehensive monitoring.

---

## 🌱 Future Scope
- Expand to other regions and integrate with real-time weather data for enhanced predictions.
- Explore drone-assisted inspections for remote validation.
- Implement blockchain for secure data tracking and accountability.

---

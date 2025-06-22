# 🔥 BAD 2.0 - Burned Area Detector Plugin for QGIS

**BAD (Burned Area Detector)** is a free and open-source QGIS plugin designed to detect and validate wildfire-affected regions using multispectral Sentinel-2 imagery. This plugin enhances the accuracy of burned area mapping through preprocessing, region growing, burn severity classification, and validation tools.

---

## 🌍 Key Features

- **Preprocessing Tool**: Mask unwanted classes from the Sentinel-2 Scene Classification Layer (SCL) to reduce error and improve analysis.
- **Feature Extraction**: Automatically computes features and membership degrees using fuzzy logic.
- **OWA Aggregation**: Integrates multiple indicators with Ordered Weighted Averaging (OWA) for burned area evidence.
- **Region Growing**: Interactive segmentation algorithm based on user-defined thresholds.
- **Burn Severity Mapping**: Supports dNBR-based classification with 7 severity levels.
- **Validation Tools**: Includes confusion matrix, accuracy metrics, and agreement map generation using reference data.
- **QGIS Integrated**: Seamlessly runs inside the QGIS environment with a user-friendly PyQt interface.

---

## 🚀 Getting Started

1. **Install QGIS**: https://qgis.org/en/site/forusers/download.html
2. **Clone this Repository**:
   ```bash
   git clone https://github.com/yourusername/BAD-Plugin.git

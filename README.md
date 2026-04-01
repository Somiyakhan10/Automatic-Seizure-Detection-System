# Advanced Seizure Detection Using Wearable Accelerometer Data

## 📄 Project Overview

This project implements an **advanced seizure detection system** using accelerometer data from wearable sensors. It processes 3-axis acceleration data, extracts time-domain and frequency-domain features, and uses a **Random Forest classifier** to detect possible seizure events. The system also visualizes detected seizure windows in the acceleration signal.

**Key highlights:**

- Uses **x, y, z accelerometer data** to compute magnitude and detect motion patterns.
- Extracts advanced features including:
  - Mean, Standard Deviation, RMS, Max/Min, Skewness, Kurtosis
  - Jerk (derivative) statistics
  - Frequency-domain features using Welch PSD
- Implements **sliding window feature extraction** for time-series segmentation.
- Classifies seizure vs normal activity using **Random Forest**.
- Highlights detected seizure windows on the raw accelerometer signal.
- Outputs a **CSV summary** with features and labels for further analysis.

---


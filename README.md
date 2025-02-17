# 🛡️ ByteGuard - AI-Powered Antivirus

ByteGuard is an intelligent antivirus solution built with machine learning to detect and mitigate malware threats. Using models for anomaly detection, CNN-based malware recognition, and NLP, ByteGuard protects your system by identifying and removing malicious files.

---

## ⚙️ Features
- **Anomaly Detection** 📈: Detects unusual behaviors that may indicate malware.
- **Malware Classification** 🐍: Classifies files as malicious or safe using CNN.
- **USB Anti-Malware** 💽: Monitors USB drives for malicious activity.

---

## 🧰 Tech Stack
- **Python** 🐍
- **Machine Learning Models**: CNN, NLP, and Anomaly Detection
- **Libraries**: TensorFlow, Sklearn, Numpy

---

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- Required libraries: `pip install -r requirements.txt`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/MohamedBoghdaddy/ByteGuard.git
   ```
2. Run the antivirus script:
   ```bash
   python usb_antimalware.py
   ```

---

## 📁 Project Structure

```plaintext
ByteGuard/
├── usb_antimalware.py         # Main script for USB protection
├── anomaly_detection_model.pkl # Anomaly detection model
├── malware_cnn.h5             # CNN model for malware detection
├── nlp_malware_model.pkl      # NLP model for text-based malware analysis
└── README.md
```

---

## 📝 License
This project is licensed under the MIT License.

Stay protected! 🛡️

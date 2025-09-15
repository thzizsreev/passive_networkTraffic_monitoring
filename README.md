# Passive Network Traffic Monitoring 🚦

A machine learning–based Intrusion Detection System (IDS) that passively analyzes network traffic to classify **benign vs. malicious flows**.  
This project leverages a **Decision Tree classifier** enhanced with a **1D Gaussian smoother** to improve detection accuracy and reduce noise in traffic patterns.

---

## 📌 Features
- Uses labeled Kaggle dataset of benign and malicious network traffic.
- Decision Tree–based classification pipeline with Gaussian smoothing for feature refinement.
- Achieves **95.4% accuracy** and **0.95 F1-score** across 77k+ traffic samples.
- Generates detailed classification reports for model evaluation.
- Passive traffic profiling approach suitable for IDS research.

---

## 📊 Results

**Performance Metrics:**

| Metric       | Benign | Malicious | Overall |
|--------------|--------|-----------|---------|
| Precision    | 1.00   | 0.92      | 0.96    |
| Recall       | 0.90   | 1.00      | 0.95    |
| F1-score     | 0.95   | 0.96      | 0.95    |
| Accuracy     |        |           | **95.43%** |

---

## 🛠 Tech Stack
- **Python 3**
- **Libraries:** pandas, numpy, scikit-learn, matplotlib
- **Dataset:** [Kaggle Network Traffic Dataset]([https://www.kaggle.com/]) (benign + malicious flows)

---

## 🚀 Getting Started

### 1. Clone the repository


### 2. Install Dependencies
- pip install -r requirements.txt

### 3.Run the notebook
- jupyter notebook NetworkTrafficAnalysis_1.ipynb


git clone https://github.com/thzizsreev/Passive_Network_Traffic.git
cd Passive_Network_Traffic

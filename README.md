# Intrusion Detection System using Deep Neural Networks (DNN)

## 📌 Overview
This project implements a Deep Neural Network (DNN) to classify network traffic as **normal** or **attack**. 
It uses a preprocessed intrusion detection dataset (e.g., UNR-IDD) to demonstrate ML-driven threat detection.

## 🛠 Tools & Technologies
- Python, TensorFlow/Keras, Pandas, NumPy, Matplotlib, scikit-learn

## 🚀 Approach
1. Load and explore the dataset (train/test split).
2. Preprocess features (scaling/encoding) and labels.
3. Build a DNN classifier with Keras.
4. Train, validate, and evaluate with confusion matrix & classification report.
5. Save results (plots/metrics) into the `results/` folder.

## 📊 Results (example targets)
- Accuracy: ~97%
- False Positive Rate reduction: ~18% vs. baseline
- Confusion matrix and ROC curve saved in `results/`

## 📁 Repository Structure
```
Intrusion-Detection-DNN/
├── dataset/
│   └── README.md            # Dataset source & download instructions
├── results/
│   └── README.md            # Place evaluation plots & reports here
├── intrusion_detection_dnn.ipynb
├── requirements.txt
└── README.md
```

## 🔗 Future Enhancements
- Add Autoencoder-based anomaly detection.
- Compare DNN with Random Forest/SVM baselines.
- Integrate streaming inference for near real-time IDS.

## ⚠️ Notes
- Do **not** commit private or proprietary datasets. Use the dataset README to point to public sources.

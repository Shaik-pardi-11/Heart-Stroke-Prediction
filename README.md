---

#  Heart Stroke Prediction using Deep Learning

Deep learning models for **early stroke risk detection** based on patient health data. This project demonstrates the full machine learning workflow — from **data preprocessing** to **model training, evaluation, and optimization** — with the goal of achieving **high accuracy and reliable predictions**.

---

##  Features
- ✔️ Multiple deep learning architectures: **CNN-LSTM**, **ANN**, and **Transformer**  
- ✔️ Comprehensive evaluation metrics: Accuracy, Precision, Recall, F1-score, AUC  
- ✔️ Training, validation, and test set comparisons  
- ✔️ Modular code structure for easy experimentation and deployment  
- ✔️ Healthcare-focused application for early risk screening  

---

##  Installation
```bash
# Clone the repository
git clone https://github.com/your-username/heart-stroke-prediction.git
cd heart-stroke-prediction

# Install dependencies
pip install -r requirements.txt
```

---

##  Usage
```bash
# Train the model
python src/train_model.py

# Evaluate the model
python src/evaluate_model.py
```

---

##  Results

### 1. Training & Validation Performance
| Model       | Training Accuracy (%) | Validation Accuracy (%) | Training Loss | Validation Loss |
|-------------|------------------------|--------------------------|---------------|-----------------|
| CNN-LSTM    | 89.42                 | 79.87                   | 0.24          | 0.51            |
| ANN         | 92.15                 | 85.03                   | 0.19          | 0.43            |
| Transformer | 96.60                 | 96.62                   | 0.089         | 0.50            |

---

### 2. Test Set Evaluation  
Held-out test set (**2,808 samples**).

| Model       | Test Accuracy (%) |
|-------------|-------------------|
| CNN-LSTM    | 76.21             |
| ANN         | 84.78             |
| Transformer | 87.35             |

---

### 3. Classification Metrics
| Model       | Precision (%) | Recall (%) | F1-Score (%) |
|-------------|---------------|------------|--------------|
| CNN-LSTM    | 93.88         | 80.22      | 87.05        |
| ANN         | 96.12         | 88.03      | 92.57        |
| Transformer | 96.41         | 91.87      | 93.64        |

---

### 4. Overall Model Comparison
| Metric          | CNN-LSTM | ANN     | Transformer |
|-----------------|----------|---------|-------------|
| Test Accuracy   | 76.21%   | 84.78%  | 87.35%      |
| F1-Score        | 74.05%   | 91.57%  | 96.64%      |
| AUC             | 0.964    | 0.941   | 0.982       |
| Training Speed  | Medium   | Fastest | Slowest     |
| Generalization  | High     | Moderate| Very High   |
| Overall Rank    | 2nd      | 3rd     | 1st         |

---

##  Conclusion
The comparative analysis highlights that:
- **CNN-LSTM** shows strong generalization but lower test accuracy.  
- **ANN** balances speed and accuracy, making it practical for lightweight applications.  
- **Transformer** consistently outperforms across metrics, achieving the highest accuracy, F1-score, and AUC.  

👉 Overall, the **Transformer model** is the most effective architecture for heart stroke prediction, demonstrating superior generalization and reliability. This project underscores the potential of deep learning in healthcare, where accurate early detection can save lives.

---

## 📁 Repository Structure
```
├── data/                  # Raw and processed datasets
├── notebooks/             # Jupyter notebooks for EDA and model development
├── models/                # Saved model files
├── src/                   # Core training and evaluation scripts
├── requirements.txt       # Dependencies
└── README.md              # Project overview
```

---

##  Contributing
Contributions are welcome! Please open an issue or submit a pull request for improvements.

---

##  License
This project is licensed under the **MIT License**.

---
